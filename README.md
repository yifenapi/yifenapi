<div align="center">


# 一分API · YiFenAPI

**一分钱用 AI，认准一分 API！花一分钱，干十分事！**

[官网](https://yifenapi.com) · [模型价格](https://yifenapi.com/pricing) · [接入文档](https://yifenapi.com/docs) · [常见问题](https://yifenapi.com/faq) · [Telegram 社群](https://t.me/yifenapicom)

</div>

---

## 关于一分API

一分API（[yifenapi.com](https://yifenapi.com)）是面向中文开发者的一站式 AI 模型 API 平台。一个 Key、一个统一接口，即可调用 Claude、GPT 全系列最新模型（DeepSeek、GLM、Qwen 即将上线）。接口与官方格式 100% 兼容，无需更换开发工具，替换 Base URL 即刻接入 Claude Code、Codex 等主流编程助手。按量计费、价格透明、无月费无订阅，额度永久有效；支持支付宝/微信付款，GitHub 一键注册，新用户即送体验额度。多节点冗余架构与专业运维保障，低延迟稳定直达。一分钱用 AI，认准一分 API！

## ✨ 核心特性

- 🔌 **统一接口**：OpenAI / Anthropic 格式全兼容，SDK、Claude Code、Codex 开箱即用
- 🚀 **模型齐全**：Claude、GPT 全系列同步更新，新模型通常 24 小时内接入
- 💰 **按量计费**：用多少付多少，无隐藏费用，充值额度永久有效
- 🇨🇳 **本地化支付**：支付宝 / 微信，无需外币信用卡
- ⚡ **注册零门槛**：GitHub 一键登录注册，30 秒开通即送体验额度
- 📊 **完整控制台**：用量统计、费用账单、Key 管理、分组折扣一目了然
- 🎁 **邀请返利**：邀请好友充值可获返利，多邀多得
- 🔒 **隐私保障**：不存代码、不存 Key，请求全程加密传输

## 🤝 生态无缝兼容

如果你用过市面上任何主流 AI API 中转/聚合平台，这里的一切都会让你倍感熟悉——**零学习成本，无缝迁移**：

- **控制台亲和**：令牌（Key）管理、分组、额度、日志、模型价格页，操作习惯与主流平台一致
- **接口亲和**：`/v1/chat/completions`、`/v1/messages`、`/v1/responses` 等标准端点，现有代码只改 Base URL 和 Key 即可切换
- **工具链亲和**：主流第三方客户端、SDK 封装、计费面板均可直接对接
- **持续迭代**：功能与安全修复持续更新，新模型第一时间接入

## 💸 分组与折扣

按需选择分组，折扣越低越省钱（示例，以 [价格页](https://yifenapi.com/pricing) 实时展示为准）：

| 分组 | 倍率 | 参考折扣 | 说明 |
|---|---|---|---|
| Claude MAX 满血分组 | 1.8× | **2.6 折** | MAX 号池满血官方直连，快又好 |
| Claude MAX Lite 分组 | 0.7× | **1 折** | 第三方 krio 反代分组，够实惠 |
| Codex 分组 | 1× | **1.4 折** | GPT / Codex 系列，极致性价比 |
| 企业版专属分组 | 定制 | 专属定制 | 首充 > ¥2,000，专属通道 + 微信技术支持群 |
| 定制专属分组 | 定制 | 专属定制 | 月充值 > ¥10,000，专享调用渠道 |

> 折扣按平台标价计算：例如 2.6 折表示标价 $10 的用量只需 $2.6。充值 1:1 记账（¥1 = $1 额度），额度永久有效。

## 🚀 30 秒接入

**Claude Code：**

```bash
export ANTHROPIC_BASE_URL="https://api.yifenapi.com"
export ANTHROPIC_API_KEY="sk-..."   # 在控制台「密钥」页面创建

claude   # 开始编码
```

**OpenAI SDK（Python）：**

```python
from openai import OpenAI

client = OpenAI(
    base_url="https://api.yifenapi.com/v1",
    api_key="sk-...",
)
resp = client.chat.completions.create(
    model="gpt-5.4",
    messages=[{"role": "user", "content": "你好"}],
)
print(resp.choices[0].message.content)
```

更多客户端（Codex、VSCode 扩展、Anthropic SDK）配置见 [接入文档](https://yifenapi.com/docs)。

## 💡 三步开始使用

1. **注册**：[GitHub 一键注册](https://yifenapi.com/sign-up) 或邮箱注册，即送体验额度
2. **创建 Key**：控制台「密钥」页面创建 API Key，选择合适的分组
3. **接入**：替换 Base URL，立即在你熟悉的工具里使用

## 📮 联系我们

| 渠道 | 地址 |
|---|---|
| Telegram 客服 | [@yifenapi](https://t.me/yifenapi) |
| Telegram 社群 | [@yifenapicom](https://t.me/yifenapicom) |

---

<sub>模型商标归各自所有者所有。本平台为独立第三方服务，与 Anthropic、OpenAI 无隶属或授权关系。</sub>
