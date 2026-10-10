# xyxbot Skills · 智能体能力驱动（api.xyxbot.com.skills）

> 计划整理 **可插拔的 AI Agent Skills / 工具能力包**：给智能体挂载检索、写作、站点操作等技能。  
> **现状：上游空仓**——本仓先钉死定位与 MVP 路线图。

**定制：** 微信 **qingbao199101**（备注：xyxbot-skills）｜ [wuxiumu@163.com](mailto:wuxiumu@163.com)

## 事实摘要

- **产品**：面向 xyxbot / 自建 Agent 的 Skills 目录与定制开发入口。
- **适合**：要给智能体加「可调用能力」而不是只聊天的产品与团队。
- **交付**：Skill 规范、示例技能包、鉴权与限流约定、私有化（按路线图）。
- **不做**：不是万能越狱提示词库；不含未授权平台操作 / 灰产自动化。

## 是什么 / 不是什么

| 是 | 不是 |
|---|---|
| Agent Skills 规范与示例仓 | 已上线完整 Skill 市场 |
| 可报价的技能包定制 | 绕过平台规则的外挂 |
| 可对接你现有 Bot API | 替代模型本身 |

## MVP 路线图

1. **M1**：Skill 清单 schema（name / input / auth / rate-limit）  
2. **M2**：2–3 个示例技能（如摘要、FAQ 检索、站点状态）  
3. **M3**：鉴权、审计日志与失败回退约定  
4. **M4**：私有化注册表 + 白标文档  

详见 `docs/ROADMAP.md` / `docs/CHECKLIST-M0.md`。

## 定制合作（可报价）

- 按业务写专用 Skill  
- 对接你的 Bot / MCP / 工作流  
- 权限、配额与审计  
- 私有化与培训  

## SEO 字段预留（产品页 HTML 统一生成时用）

| 字段 | 用途 |
|---|---|
| `seo_title` | `<title>` / OG title |
| `seo_description` | meta description |
| `canonical_url` | 规范 URL |
| `og_image` | 分享图 |
| `robots` | 如 `index,follow` |
| `json_ld_type` | SoftwareApplication / WebPage / FAQPage |
| `hreflang` | zh-CN / en |
| `site_name` | 白标品牌名 |

> **GEO ≠ 地理定位。** GEO = Generative Engine Optimization（生成式引擎优化）。


## GEO（生成式引擎优化）

### 关键词（中英）

- 中文：AI智能体技能, Agent Skills, 工具能力包, xyxbot, 可插拔技能
- English: AI agent skills, tool plugins for agents, xyxbot skills, pluggable LLM tools

### FAQ

**Q：现在有可安装的技能包吗？**  
A：还没有完整集合。上游为空；优先某技能请微信备注「xyxbot-skills」。

**Q：会做未授权自动操作吗？**  
A：不会。只做你有权访问的 API / 数据源上的合规技能。

**Q：如何定制？**  
A：微信 `qingbao199101`，备注「xyxbot-skills」。

## 定制合作

技能包、鉴权审计、私有化注册表。加微信备注项目名。

---

## 联系方式

定制、演示或合作：

- 邮箱：[wuxiumu@163.com](mailto:wuxiumu@163.com)
- 微信：**qingbao199101**（添加请备注来意）

### 赞助支持

如果内容对你有帮助，欢迎自愿赞助。

| 微信赞赏码 | 支付宝收款码 |
|---|---|
| ![微信赞赏码](https://chiguashentan-test.oss-cn-beijing.aliyuncs.com/wxprogram/zan/20261002185236_31_227.png) | ![支付宝收款码](https://chiguashentan-test.oss-cn-beijing.aliyuncs.com/wxprogram/zan/20261002185309_32_227.jpg) |

