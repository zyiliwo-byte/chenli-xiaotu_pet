# 陈粒小兔 Codex 宠物

这是一个 Codex Desktop 自定义宠物：小兔。

## 一键安装

在 Codex 里新开一个对话，把下面这段话直接发给 Codex：

```text
请帮我安装这个 Codex 桌面宠物：

宠物名称：小兔
宠物 ID：line-sprout
pet.json：
https://raw.githubusercontent.com/zyiliwo-byte/chenli-xiaotu_pet/main/pets/line-sprout/pet.json
spritesheet.webp：
https://raw.githubusercontent.com/zyiliwo-byte/chenli-xiaotu_pet/main/pets/line-sprout/spritesheet.webp

请把它安装到我的本地 Codex 宠物目录：
~/.codex/pets/line-sprout/

安装完成后，请提醒我在 Codex Desktop 里打开：
Settings -> Appearance -> Pets -> Refresh custom pets
然后选择「小兔」。
```

安装后，如果 Codex 还没有自动提醒你，在 Codex Desktop 里打开：

```text
Settings -> Appearance -> Pets -> Refresh custom pets
```

然后选择 `小兔`。

## 状态预览

标记为 `常见` 的状态是日常使用里最容易看到的几种状态。

| 状态 | 出现频率 | 说明 | 预览 |
| --- | --- | --- | --- |
| `idle` | 常见 | 默认/空闲状态。 | ![idle](pets/line-sprout/previews/idle.gif) |
| `running` | 常见 | Codex 正在执行任务、思考、调用工具或改文件。 | ![running](pets/line-sprout/previews/running.gif) |
| `waiting` | 常见 | Codex 等待你的输入、确认或授权。 | ![waiting](pets/line-sprout/previews/waiting.gif) |
| `review` | 常见 | Codex 在检查、总结或等你查看结果。 | ![review](pets/line-sprout/previews/review.gif) |
| `failed` | 较少 | 任务失败或遇到错误时。 | ![failed](pets/line-sprout/previews/failed.gif) |
| `waving` | 较少 | 打招呼、唤醒或短暂互动。 | ![waving](pets/line-sprout/previews/waving.gif) |
| `jumping` | 较少 | 特殊反馈或短暂庆祝。 | ![jumping](pets/line-sprout/previews/jumping.gif) |
| `running-right` | 较少 | 方向性移动/过渡状态。 | ![running-right](pets/line-sprout/previews/running-right.gif) |
| `running-left` | 较少 | 方向性移动/过渡状态。 | ![running-left](pets/line-sprout/previews/running-left.gif) |

## 文件结构

```text
pets/
  line-sprout/
    pet.json
    spritesheet.webp
    previews/
      idle.gif
      running.gif
      waiting.gif
      review.gif
      failed.gif
      waving.gif
      jumping.gif
      running-right.gif
      running-left.gif
```
