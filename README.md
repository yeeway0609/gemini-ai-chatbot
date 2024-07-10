# Gemini AI bot

## Get API Key
Go to [Google AI Studio dashboard](https://aistudio.google.com) and get your API key.

You can quickly test the API by running a cURL command:
```
curl \
  -H 'Content-Type: application/json' \
  -d '{"contents":[{"parts":[{"text":"Explain how AI works"}]}]}' \
  -X POST 'https://generativelanguage.googleapis.com/v1beta/models/gemini-1.5-flash-latest:generateContent?key=YOUR_API_KEY'
```

## 注意事項
API key 是不能對外公開的，本次練習只是為了方便實作所以將程式碼都寫在前端 HTML 檔上，需要實作的話請使用環境變數存放 API key.
