# Personal 1Panel App Store

**Language:** English | [简体中文](README_zh-CN.md)

A custom application store for [1Panel](https://github.com/1Panel-dev/1Panel) featuring auto-update capabilities for third-party applications.

## 📱 Featured Applications

- [NapCat](https://github.com/NapNeko/NapCatQQ) - Modern protocol-side framework based on NTQQ
- [OI-Bot](https://github.com/yuhiri/OI-Bot/) - A chatbot based on the Nonebot2 framework to provide relevant information for OIers and ACMers.

## ✨ Features

- 🔄 **Automated Updates** - Version updates managed via Renovate
- 📦 **Easy Installation** - Simplified installation script
- 🤖 **CI/CD Integration** - GitHub Actions workflows for automation

## 🚀 Quick Start

### One-Command Installation

Run this single command to download and execute the installation script:

```bash
bash <(curl -sL "https://raw.githubusercontent.com/yuhiri/appstore-1panel/refs/heads/main/install_app.sh")
```

**Alternative mirrors (for mainland China users):**

```bash
# Using Gitee mirror (recommended for China)
bash <(curl -sL "https://gitee.com/yuhiri/appstore-1panel/raw/main/install_app.sh")
```

### Installation

What the script will do:

1. Clone the repository from main branch
2. Copy applications to 1Panel local app directory
3. Install environment files
4. Clean up temporary files
