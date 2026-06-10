# zhouli-copywriter

一个用于生成“大周礼时代”文案的 Codex Skill。

它会把日常劝告、群聊回应、朋友圈评论、朋友间调侃，改写成庄重的现代白话翻译腔：像是在翻译古文，又带着“合乎周礼 / 不周礼”的互联网梗味。

## 适合场景

- 生成周礼文案、大周礼时代文案
- 回应“合乎周礼吗”“不周礼”一类梗
- 用古文翻译腔劝朋友
- 把吵架、熬夜、拖延、不回消息、嘴硬等日常小事写成礼法式劝告
- 给群聊、评论区、朋友圈写温和但端着的整活文案

## 示例提示词

```text
用 zhouli-copywriter 写一段劝朋友别熬夜的周礼文案
```

```text
生成一段大周礼时代文案，主题是朋友已读不回
```

```text
有人骂我，帮我写一段不直接引用对方原话的周礼式回应
```

## 风格要点

- 以“我曾经听说”开头
- 使用自然意象和排比句
- 采用“古时候的人之所以……是因为……”的翻译腔
- 把现代小事上升为礼义、君子、和气、秩序的问题
- 语气温厚，不直接对骂
- 最后落到“合乎周礼 / 不合周礼 / 还请思量其中道理”

## 安装

将本仓库放到 Codex skills 目录中：

```powershell
git clone https://github.com/ygpdzd/zhouli-copywriter.git C:\Users\86158\.codex\skills\zhouli-copywriter
```

如果已经在该目录中，可以直接更新：

```powershell
cd C:\Users\86158\.codex\skills\zhouli-copywriter
git pull
```

## 目录结构

```text
zhouli-copywriter/
├── SKILL.md
├── agents/
│   └── openai.yaml
└── references/
    └── style-patterns.md
```
