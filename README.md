# 📝 Trionote 项目说明 (Project Overview)

**Trionote** 是一款基于纯 HTML5 构建的轻量级、沉浸式网页备忘录工具。它集成了高效的本地存储方案与现代化的 UI 交互设计，提供了一个安全、丝滑的写作环境。

**Trionote** is a lightweight, immersive web-based note-taking tool built with pure HTML5. It integrates efficient local storage solutions with modern UI interaction design to provide a secure and smooth writing environment.

**[🚀 在线体验 Demo (Live Demo)](https://xiaowugd.github.io/Trionote/)**

---

## ✨ 核心特点 (Key Features)

* **🎨 视觉设计 (Visual Design)**：内置 8 套个性化主题，支持跟随系统自动切换。
* Built-in 8 personalized themes with support for automatic system-based switching.


* **📱 移动端适配 (Mobile Optimization)**：
* **层级导航 (Hierarchical Navigation)**：在手机端实现列表与编辑页的切换。
* Seamless switching between list and editor views on mobile devices.


* **交互适配 (Interaction Adaptation)**：专门适配了移动端悬浮按钮 (FAB)。
* Specifically adapted mobile Floating Action Button (FAB).




* **🔐 隐私安全存储 (Privacy & Secure Storage)**：数据完全存储于浏览器本地的 `IndexedDB`（数据库名：`TrioNote`），不使用任何后端。
* Data is stored entirely in the browser's local `IndexedDB` (Database name: `TrioNote`), requiring no backend.


* **✍️ 写作体验 (Writing Experience)**：
* 采用 **Quill.js** 现代富文本编辑器。
* Utilizes the **Quill.js** modern rich text editor.


* 支持独立字号缩放。
* Supports independent font size scaling.




* **📦 灵活的数据管理 (Flexible Data Management)**：
* **导入 (Import)**：支持批量导入 TXT 文本或 ZIP 压缩包。
* Supports bulk importing of TXT files or ZIP archives.


* **导出 (Export)**：支持选择性导出或全量备份为 ZIP 格式（内含标准 HTML 文件）。
* Supports selective or full backup to ZIP format (containing standard HTML files).




* **⚡ 极致性能 (Ultimate Performance)**：采用单文件架构，代码简洁，提供原生应用般的流畅感。
* Single-file architecture with clean code, providing a native app-like smoothness.



## 🛠️ 技术栈 (Tech Stack)

* **编辑器核心 (Editor Core)**：[Quill.js](https://quilljs.com/)
* **列表排序 (List Sorting)**：[Sortable.js](https://sortablejs.com/)
* **数据压缩 (Compression)**：[JSZip](https://stuk.github.io/jszip/)
* **本地存储 (Local Storage)**：Browser IndexedDB

## 📄 开源协议 (License)

本项目采用 **MIT License** 开源。
This project is open-sourced under the **MIT License**.

Copyright (c) 2026 **xiaowugd**
