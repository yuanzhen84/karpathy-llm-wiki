# Karpathy LLM Wiki

这是一篇关于使用 Obsidian、Claude Code 和 html-anything 搭建 Karpathy 式个人知识库的实践文章。

在线阅读：

https://yuanzhen84.github.io/karpathy-llm-wiki/

## 文件结构

```text
.
├── index.html
├── source/
│   └── Karpathy LLM Wiki.md
├── archive/
│   └── 2026-05-20-karpathy-llm-wiki-article-magazine-v1.html
└── CHANGELOG.md
```

- `index.html`: 当前正式发布页面。
- `source/`: Markdown 源文快照，真正的工作源文件仍在 Obsidian Vault 中维护。
- `archive/`: 历史 HTML 版本归档，用于回滚和对比。

## 生成流程

```text
Obsidian Markdown
  -> html-anything article-magazine 模板
  -> 本地检查和微调
  -> index.html
  -> GitHub Pages
```

