# paper-review-board
A lightweight, privacy-first, single-HTML tool for tracking academic paper submissions and peer reviews. 一款纯前端、数据存本地的极简学术投稿与审稿管理工具。

# 📑 学术投稿与审稿管理工具 (Academic Tracker)

> 一款为科研工作者量身定制的轻量级、零部署、绝对隐私的单文件（Single-HTML）管理工具。
<img width="400" alt="1" src="https://github.com/user-attachments/assets/9d63750a-d10f-4001-813f-88ccfcc21510" />  <img width="400"  alt="2" src="https://github.com/user-attachments/assets/e04e5985-963c-4878-99c9-5b2f0ccce824" />



## 💡 起因
都说搞论文比较好的状态是：“一个在投，一个返修，一个在写，一个在构思”。
为了解决日常科研中**“稿件进度难追踪、不同期刊账号易遗忘、审稿 DDL 容易错过、缺乏数据复盘”**等痛点，我基于日常需求 Vibe Coding 了这款极简工具。

**纯前端原生代码（Vanilla JS + HTML + CSS），数据 100% 存在浏览器本地（LocalStorage），不需联网，不走服务器，绝对保护未发表论文的隐私安全。**

## ✨ 核心功能

<img width="410"  alt="3" src="https://github.com/user-attachments/assets/4c39c6c7-53df-4c64-a79d-c443fca2f4c2" /> <img width="410" alt="4" src="https://github.com/user-attachments/assets/590d45c4-fb00-4039-aaa1-507e2a562a92" />
<img width="392" height="621" alt="5" src="https://github.com/user-attachments/assets/451000bd-220c-4719-a1c7-45b2111a31ae" /> <img width="392" height="621" alt="6" src="https://github.com/user-attachments/assets/84470104-03f3-42a1-93c2-281b629c25c5" />




### 📄 投稿管理 (Paper Submissions)
- **状态流转**：准备中 → 已投稿 → 审稿中 → 修回中 → 接收/被拒。
- **多轮历史串联**：支持将同一篇论文被拒后的转投记录关联，生成完整的“悲剧与重生”历史。
- **独立密码本**：每篇稿件绑定独立的「🔑 账号/密码」备忘录，解决各个系统密码遗忘的烦恼。
- **自定义时间线**：完整记录 With Editor, Under Review 等每一个时间节点。

### 📋 审稿追踪 (Peer Reviews)
- **双轨制看板**：投稿与审稿独立双看板，无缝切换。
- **审稿决策记录**：记录邀请时间、审稿轮次，并根据你的决定（接收/小修/大修/拒稿）自动沉底归档已完成的任务。

### 📊 可视化与提醒 (Dashboard & Alerts)
- **自动 DDL 预警**：距离返修或审稿截止日期不到 7 天时，自动高亮红色预警。
- **多维统计图表**：内置 Chart.js，自动生成按年/月维度的投稿与审稿走势曲线、接收/拒稿率饼图，支持按期刊与年份动态筛选。

## 🚀 如何使用 (How to use)

本项目**无需任何安装、配置或后端部署**，非常适合非计算机背景的科研人员：

1. 点击本仓库上方的 `Code` 按钮，下载 ZIP 压缩包并解压，或者直接打开 `index.html` 的源码。
2. 将 `index.html` 文件保存在你的电脑本地。
3. **双击该文件**，它会在你的默认浏览器中打开。
4. 开始记录你的科研日常吧！（支持将文件传到手机端浏览器直接打开使用）

*💡 提示：为了防止清理浏览器缓存导致数据丢失，请定期在界面右上角点击「📋 导出备份」，将数据保存为 JSON 文件。*

**🎁 附赠测试数据：** 本项目内置了一份 example_data.json 测试文件。你可以下载后，在工具右上角点击「📥 导入」，直接体验带图表统计的完整效果！

## 🛠️ 技术栈
- HTML5 + CSS3 (原生，无预处理器)
- Vanilla JavaScript (ES6+)
- [Chart.js](https://www.chartjs.org/) (用于数据可视化统计)
- `localStorage` (本地数据持久化)

## ✉️ 作者与交流
- **小红书主页**：@不要瞎说 (ID: 9559301087)
- **联系与合作交流**：academic.zst@outlook.com

## 📜 许可声明
本项目代码开源，仅供科研、学习及个人日常工作交流使用，**请勿用于任何商业用途**。
