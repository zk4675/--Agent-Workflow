🤖 QA-Agent-Workflow: 智能测试规范与用例格式化 Agent

基于大语言模型（LLM）与 RAG（检索增强生成）技术的自动化测试辅助智能体。将测试人员的“大白话”测试思路，秒级转化为格式极其严密的标准化测试用例。

## 🌟 项目亮点
- **多意图精准路由：** 通过 LLM 节点前置意图识别，分离测试设计与闲聊需求。
- **RAG 知识库增强：** 挂载企业级测试规范与 P0/P1 定级标准，杜绝模型幻觉。
- **强制结构化输出：** 利用强大的 Prompt Engineering，强制将非结构化输入转化为包含“前置条件、测试步骤、预期结果、优先级”的严谨 Markdown 结构。
- **零代码/低代码编排：** 基于 Coze 平台搭建，支持快速迭代与多端（飞书/钉钉/API）发布。

## 📂 仓库目录结构
* `Prompts/`: 核心大模型的 System Prompts 备份。
* `Knowledge_Base/`: RAG 知识库脱敏测试模板样例。
* `Architecture/`: Agent 工作流架构图。
* `main.py`: 基于 Coze API 封装的本地调用脚本。

## 🖼️ 架构图与效果演示

<img width="1894" height="562" alt="a7352ac9-09f5-42d8-8dd1-3a3d649ff09b" src="https://github.com/user-attachments/assets/c1caa52f-8c2e-4393-953c-b6d3bee5dbf3" />


## 🚀 业务价值
将手工用例的排版与格式化时间缩短 80%，有效避免因个人经验导致的漏测，统一团队测试产出规范。
