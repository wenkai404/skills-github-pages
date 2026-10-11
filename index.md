<!DOCTYPE html>
<html lang="zh-CN">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>我的第一个 GitHub Pages 网站</title>
    <style>
        * { margin: 0; padding: 0; box-sizing: border-box; }
        body {
            font-family: -apple-system, "Segoe UI", "Microsoft YaHei", sans-serif;
            line-height: 1.7;
            color: #24292f;
            background: #f6f8fa;
            padding: 40px 20px;
        }
        .container {
            max-width: 720px;
            margin: 0 auto;
            background: #fff;
            border-radius: 12px;
            padding: 48px 40px;
            box-shadow: 0 2px 12px rgba(0,0,0,0.08);
        }
        h1 { font-size: 2em; margin-bottom: 16px; }
        h2 { font-size: 1.4em; margin: 32px 0 12px; border-bottom: 1px solid #eaecef; padding-bottom: 6px; }
        p { margin-bottom: 14px; }
        ul { margin: 0 0 14px 24px; }
        li { margin-bottom: 6px; }
        code {
            background: #f6f8fa;
            padding: 2px 6px;
            border-radius: 4px;
            font-family: Consolas, Monaco, monospace;
            font-size: 0.9em;
        }
        .badge {
            display: inline-block;
            background: #0969da;
            color: #fff;
            padding: 4px 12px;
            border-radius: 20px;
            font-size: 0.85em;
            margin-bottom: 20px;
        }
        footer {
            margin-top: 40px;
            padding-top: 20px;
            border-top: 1px solid #eaecef;
            color: #57606a;
            font-size: 0.9em;
        }
    </style>
</head>
<body>
    <div class="container">
        <span class="badge">GitHub Pages</span>
        <h1>👋 你好，世界！</h1>
        <p>这是我用 GitHub Pages 部署的第一个网站。它由 <code>main</code> 分支里的文件自动渲染生成。</p>

        <h2>关于这个页面</h2>
        <ul>
            <li>托管在 GitHub 的免费服务器上</li>
            <li>每次 push 到 <code>main</code> 分支，网站会自动更新</li>
            <li>完全不需要自己买服务器</li>
        </ul>

        <h2>我学会了什么</h2>
        <ul>
            <li>如何创建分支并开发</li>
            <li>如何发起 Pull Request</li>
            <li>如何合并分支</li>
            <li>如何用 GitHub Pages 发布网站</li>
        </ul>

        <h2>访问地址</h2>
        <p>网站地址格式为：<code>https://你的用户名.github.io/仓库名/</code></p>

        <footer>
            © 2026 我的第一个 Pages 网站 · 用 Markdown 和 Git 搭建
        </footer>
    </div>
</body>
</html>
