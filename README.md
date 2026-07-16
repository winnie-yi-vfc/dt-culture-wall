# DT Culture Wall

DT Shanghai Office 的文化墙互动展示页面。运行在办公室大屏上，用于团队文化建设。

## 功能

- 6 页幻灯片轮播展示（键盘左右箭头切换）
- **Identity** — DT 团队身份与使命
- **People** — 团队结构与新成员
- **Recognition** — 表彰与成就展示
- **Learning** — 学习成长故事
- **Social** — 团队活动与生日
- **Interactive** — 互动反馈入口
- 底部导航点，点击跳转任意页面

## 技术栈

- 纯静态 HTML + CSS + JavaScript
- 无框架依赖
- 字体：Google Fonts (Archivo Black, Space Grotesk, Manrope, JetBrains Mono)
- 部署方式：直接浏览器打开 index.html

## 文件结构

```
/                          # 项目根目录
  index.html               # 唯一入口文件，包含所有 HTML/CSS/JS
  README.md                # 本文件，项目唯一真相源
```

## 给 AI 的约束

- 本文件（README.md）是项目唯一真相源，修改功能前先读这里
- 所有代码在 index.html 中，不要创建新文件除非明确要求
- 字体方案已固定，不要更换 Google Fonts 引用
- 颜色变量定义在 :root 中，修改配色只改 CSS 变量
- 新增幻灯片时保持现有 slide 结构（.slide > .slide-number + .content）
- 保持现有 6 张幻灯片数量，如需增减先确认
- 提交信息格式：feat: / fix: / docs: 开头
- 分支策略：AI 只允许在 `ai-wip` 分支工作，由人工审核后合并到 `main`

## 运行方式

直接用浏览器打开 index.html，或通过任意静态文件服务器托管。
