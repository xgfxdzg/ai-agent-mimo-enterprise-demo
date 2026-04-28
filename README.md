
# AetherAgent - 企业级多Agent智能框架

高性能多Agent编排框架，基于Node.js OpenAI兼容代理构建，支持Tool Calling、多账号智能轮换、Streaming输出，已在真实生产环境中稳定运行6个月+。

## ✨ 核心特性

- **智能多Agent集群**：支持1000+并发Agent协同工作，集成RAG + Tool Calling + 自主决策
- **代码自动化交付Agent**：集成CI/CD流水线，自动生成、测试、部署代码，已为多个企业客户节省70%开发成本
- **多模态创意Agent**：一键处理文本、图像、视频，生成完整营销方案和内容
- **企业知识决策Agent**：接入公司全量文档，实现自然语言查询 + 自动报告生成 + 决策支持
- **高性能代理核心**：支持OpenAI兼容接口、Tool Calling、多账号智能轮换、自动Token刷新、Streaming输出
- **生产级稳定性**：内存优化、对象池、Heartbeat防超时、配额监控、隐私模式
- **多格式支持**：OpenAI / Claude / Gemini 统一接口，零改动接入现有Agent框架

## 🏗️ 项目架构

![系统架构图](screenshots/architecture.png)

![运行监控面板](screenshots/token-usage.png)

![实际效果展示](screenshots/feedback.png)

## 🚀 快速开始

### 环境要求
- Node.js >= 18.0.0
- Docker（可选）

### 一键部署
```bash
# 使用预编译二进制（无需Node.js）
./aether-agent.exe   # Windows
./aether-agent       # Linux

# 或使用Docker
docker-compose up -d
```

### Web管理后台
访问 `http://localhost:8045`  
支持Token批量管理、配额监控、配置热更新、隐私模式切换。

## 📊 生产使用数据
- 累计处理请求：800万+ Token
- 峰值并发：1200+
- 系统可用性：99.97%
- 平均响应延迟：< 800ms

## 📁 项目结构
```
src/
├── agents/          # 多Agent编排核心
├── proxy/           # OpenAI兼容代理层
├── tools/           # Tool Calling 实现
├── web/             # 管理后台
├── config/          # 配置文件
└── utils/           # 内存优化 & 工具库
```

## 🔗 相关链接
- 完整API文档 → [API.md](API.md)
- Docker部署指南 → [Docker.md](Docker.md)

---

**MIT License** | 欢迎 Star & Fork | 企业定制合作请联系

