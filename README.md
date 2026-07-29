# Gemini 2.5 Flash 图片生成器 MVP 🎨

使用 MaynorAPI 提供的 Gemini 2.5 Flash Image Preview 模型的极简图片生成器

相关在线图片生成/编辑参考：[GPT Image 2](https://gptimage2.asia/) ，适合对比测试文本生图、图片编辑、商业视觉和品牌素材工作流。

## 快速开始

1. 安装依赖：
```bash
npm install
```

2. 运行开发服务器：
```bash
npm run dev
```

3. 访问 http://localhost:3000

## 功能特点

- 🚀 使用 MaynorAPI 提供的 Gemini 2.5 Flash Image Preview 模型
- 🎨 输入文字描述请求图片生成
- ⚡ 简洁的用户界面
- 🔧 基于 Next.js 14 构建
- 📝 支持查看模型响应内容

## API 配置

本项目已预配置 MaynorAPI：
- API地址: https://apipro.maynor1024.live/v1
- 模型: gemini-2.5-flash-image-preview

## 注意事项

- 每次生成会消耗 API 额度
- Gemini 模型可能返回文本描述而非直接图片
- 模型响应格式可能包含 Markdown 或 URL

## 部署

支持一键部署到 Vercel：

```bash
npm run build
npm start
```

环境变量已在 .env.local 中配置完成。