<p align="center">
  <img src="https://img.shields.io/badge/Status-Active-success?style=flat-square" />
  <img src="https://img.shields.io/badge/License-MIT-blue?style=flat-square" />
  <img src="https://img.shields.io/badge/Platform-OpenClaw-8A2BE2?style=flat-square" />
  <img src="https://img.shields.io/badge/AI%20Agent-Skill-FF6B6B?style=flat-square" />
</p>

<h1 align="center">
  📊 Cross-Axis Analysis
</h1>
<h3 align="center">
  横纵分析法 · Cross-Axis Analysis Framework
</h3>
<p align="center">
  <em>纵向时间深度 ✕ 横向竞争格局 = 系统性认知</em>
</p>

---

## 📖 这是什么？

一个系统化的 **跨领域研究框架**，专为 AI Agent 深度研究设计。

当需要快速了解一个陌生领域——产品、公司、技术、人物、趋势——普通搜索只能看到"现在有什么"，而 **横纵分析法** 帮你看到"它是怎么走到今天的"和"它在竞品中处于什么位置"。

> **一句话：** 纵看历史脉络，横看竞争格局，交汇得出真正洞察。

---

## 🏗️ 框架速览（一图流）

```
┌──────────────────────────────────────────────────────────────────┐
│                         Research Subject                           │
│                 (Product / Company / Tech / Trend)                  │
└──────────────────────────────────┬────────────────────────────────┘
                                   │
              ┌────────────────────┼────────────────────┐
              ▼                    ▼                    ▼
┌─────────────────────────┐ ┌──────────────┐ ┌──────────────┐
│  Longitudinal Analysis  │ │   Cross-sec  │ │  Synthesis   │
│      (Timeline)         │ │  (Landscape) │ │  & Insights  │
├─────────────────────────┤ ├──────────────┤ ├──────────────┤
│ • Origins & context     │ │ • Tech route │ │ Past shapes  │
│ • Key turning points    │ │ • Product    │ │ today's      │
│ • Decision logic        │ │ • Business   │ │ advantages + │
│ • Path dependency       │ │ • Users      │ │ disadvantages│
│                         │ │ • Reputation │ │              │
│ Focus on causality,     │ │ • Team       │ │ 1-3 year     │
│ not dry chronology      │ │ • Funding    │ │ outlook      │
└─────────────────────────┘ └──────────────┘ └──────────────┘
```

---

## 🎯 适用场景

| 场景 | 推荐版本 | 预期产出 |
|------|---------|---------|
| 🎓 学术研究 / 文献综述 | **深度版** | 完整发展脉络 + 竞品对比 |
| 🏫 选校 / 选公司决策 | **深度版** | 生态位分析 + 横纵交汇判断 |
| 💰 投资分析（币/股） | **深度版** | 路径依赖分析 + 未来展望 |
| ⚡ 快速了解新领域 | **快速版** | 3 个转折点 + 3 个竞品 |
| 📚 小说世界观调研 | **深度版** | 同类作品生态位 + 差异化机会 |
| 📱 产品分析 | **深度版** | 技术路线 + 商业模式对比 |

---

## 🚀 快速开始

### 深度版（完整研究）

用以下 Prompt 模板，填入研究对象，发给 AI（ChatGPT Deep Research / Claude / Gemini）：

```markdown
用横纵分析法深度研究 [研究对象]：

1. 纵向：起源 → 关键转折点（至少 3 个） → 每个转折的决策逻辑 → 路径依赖分析
2. 横向：列出 3~5 个主要竞品，从技术路线/产品形态/商业模式/目标用户等多维度对比
3. 交汇：历史决策如何塑造了今天的格局？未来 1~3 年的关键变量是什么？

风格像深度报道，有叙事感，每观点有事实支撑。总计 10,000~30,000 字。
```

### 快速版（3 分钟速览）

```markdown
横纵快速分析 [研究对象]：
1. 纵向：起源 + 3 个转折点
2. 横向：3 个竞品，每点一句话
3. 交汇：100 字综合判断 + 未来展望
总字数 ≤ 1,500 字
```

---

## 📊 为什么有效？

### 多数研究方法的问题

- ❌ **只有纵向：** "公司从成立至今"→ 干了巴巴的时间线，没有竞争定位
- ❌ **只有横向：** "竞品对比" → 不知道核心竞争力从哪来的
- ❌ **没有交汇：** 两个维度各自独立，洞察断层

### 横纵分析法的独特优势

```
纵向提供深度     → 理解"为什么会成这样"
横向提供广度     → 理解"它在什么位置"
交汇产出洞察     → 理解"它应该往哪走"
```

---

## 🛠️ 技术细节

- **类型：** OpenClaw AgentSkill
- **安装：** `clawhub install cross-axis-analysis`
- **版本选择：**
  - 📗 **深度版：** 10,000~30,000 字，完整研究报告
  - 📘 **快速版：** ≤1,500 字，适合紧急判断
- **依赖：** 需要 AI 具备深度研究能力（ChatGPT Deep Research / Claude / Gemini 等）

---

## 📖 完整模板

完整 Prompt 模板见 [`references/prompt-template.md`](references/prompt-template.md)，包含：
- 详细的纵向/横向/交汇分析引导问题
- 写作风格要求
- 篇幅控制参考

---

## 📄 License

MIT © [zcz-user](https://github.com/zcz-user)
