# 我的个人博客

这是一个使用Hexo框架构建的简单个人博客，部署在GitHub Pages上。

## 项目结构

- `_config.yml`: Hexo配置文件
- `source/_posts/`: 博客文章
- `source/about/`: 关于页面
- `themes/landscape/`: 默认主题
- `scaffolds/`: 文章模板

## 安装依赖

由于环境问题，请手动安装依赖：

```bash
npm install
```

或

```bash
yarn install
```

## 本地预览

```bash
hexo server
```

## 生成静态文件

```bash
hexo generate
```

## 部署到GitHub Pages

```bash
hexo deploy
```

配置文件中已设置部署到 https://github.com/wy2025free/wy2025free.github.io.git 的main分支。

## 中文注释

- 配置文件中设置了中文语言和时区
- 文章和页面使用中文内容
- 主题支持中文显示

## 注意事项

- 确保安装了Node.js和Hexo CLI
- 如果npm有问题，可以使用yarn或手动修复npm
- GitHub Pages可能需要几分钟生效