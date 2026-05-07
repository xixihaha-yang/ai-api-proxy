# 🚀 AI API Proxy

Affordable OpenAI-compatible API endpoint for DeepSeek and other AI models.

**Pay with USDT (TRC20) | No registration required | API key in minutes**

---

## ✨ Why Use This?

| Feature | Details |
|---------|---------|
| ⚡ **Ultra Low Latency** | Singapore server, avg < 800ms |
| 🔌 **Drop-in Replacement** | 100% OpenAI SDK compatible |
| 💰 **Up to 90% Cheaper** | DeepSeek from $0.14/1M tokens |
| 🔒 **Privacy First** | No request logging |
| 💵 **Pay with USDT TRC20** | No credit card needed |

---

## 🤖 Supported Models

| Model | Type | Notes |
|-------|------|-------|
| `deepseek-chat` | Chat | Best value, GPT-4 level quality |
| `deepseek-reasoner` | Reasoning | Advanced reasoning tasks |
| `gpt-4o-mini` | Chat | Fast & cheap |

---

## 💰 Pricing

| Plan | Price | Tokens | Per 1M |
|------|-------|--------|--------|
| Starter | $5 USDT | 1M | $5.00 |
| Basic | $20 USDT | 5M | $4.00 |
| Pro | $50 USDT | 15M | $3.33 |
| Enterprise | $100 USDT | 40M | $2.50 |

---

## 🚀 Quick Start

### 1. Get Your API Key

Contact: **514414907@qq.com**

Send USDT → receive API key within 5 minutes.

---

### 2. Use It (Python)

```python
import openai

client = openai.OpenAI(
    api_key="YOUR_API_KEY",  # key we provide
    base_url="http://45.77.246.243:3000/v1"
)

response = client.chat.completions.create(
    model="deepseek-chat",
    messages=[{"role": "user", "content": "Hello!"}]
)
print(response.choices[0].message.content)
3. Use It (Node.js)
javascript
复制
import OpenAI from "openai";

const client = new OpenAI({
    apiKey: "YOUR_API_KEY",
    baseUrl: "http://45.77.246.243:3000/v1"
});

const response = await client.chat.completions.create({
    model: "deepseek-chat",
    messages: [{ role: "user", content: "Hello!" }]
});
console.log(response.choices[0].message.content);
4. Use It (curl)
bash
复制
curl http://45.77.246.243:3000/v1/chat/completions \
  -H "Content-Type: application/json" \
  -H "Authorization: Bearer YOUR_API_KEY" \
  -d '{
    "model": "deepseek-chat",
    "messages": [{"role": "user", "content": "Hello!"}]
  }'
📧 Contact
Email: 514414907@qq.com
Server: Singapore
Payment: USDT (TRC20)
Affordable AI API access for developers worldwide.
