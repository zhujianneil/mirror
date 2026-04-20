<div align="center">

# 🪞 观己 · InnerMirror

**把对话当镜子,借 AI 看见自己**
**Use conversation as a mirror. Let AI be your witness.**

一个用于 Claude 的 vipassanā 式自我观察 skill
*A vipassanā-style self-observation skill for Claude*

[English](#english) · [中文](#中文)

</div>

---

## 中文

### 这是什么

**观己**不是对话分析工具,不是聊天复盘助手,不是给情商打分的东西。

它是一面**镜子**。

你把一段对话喂给它——可以是会议录音转录、一段微信聊天、一篇日记、一次谈判复盘——它不做裁判,不给建议,它只做一件事:**把你在那个场里的真实运作放回你面前**。

> 这不是读心。这是帮你看清楚自己——你以为自己在做什么,和你实际在做什么之间的那个缝。

### 为什么需要它

人很难看清自己。不是因为不聪明,是因为**观察者和被观察者是同一个人**。你在对话里的每一次让步、每一次强势、每一次回避、每一次插话——都是无意识的动作,事后回忆全是合理化过的版本。

vipassanā(内观)的核心是:**让一个冷静的观察者站出来看**。但人自己做观察者,很难持续冷静。AI 没这个困难。

**观己**把 AI 外包成那个观察者——你看见的不是 AI 的判断,是**你自己本来存在但看不到的那些动作**。

### 产出什么

给 `观己` 一段对话,它会还给你:

- **说话人的心智轨迹** · 每个人在对话中的真实动机演化,不只是表面说了什么
- **信号地图** · 谁在发出什么信号,什么信号被接收了,什么被忽略了
- **场的诊断** · 这个对话场的真实权力结构、情绪底色、未说出口的那条线
- **你的位置** · **这是核心** — 你在这个场里扮演了什么角色,你以为的你和实际的你之间,差在哪里

### 怎么用

**前置:** 你需要有skills 的环境（claude最佳，各种龙虾openclaw亦可 ）。

```bash
# Clone to your skills directory
git clone https://github.com/zhujianneil/mirror.git ~/.claude/skills/neil-mirror

# In Claude, trigger it:
# "用观己分析这段对话:[粘贴对话内容]"
# Or: "帮我用 mirror 看看我在这个会议里的位置"
```

### 适合什么场景

- **重要会议后的 10 分钟** — 趁记忆还热
- **谈判/面试/约会之后** — 你真的控场了吗?还是你以为你控场了?
- **和家人/伴侣的冲突复盘** — 那些"我只是想..."的背后
- **自己和自己的对话** — 日记、内心独白、决策时的反复权衡

### 不适合什么

- ❌ 给别人心理画像(这是工具滥用)
- ❌ 在对话进行时实时分析(你应该在场,不是在看)
- ❌ 代替真实的关系、治疗、冥想练习

---

## English

### What is this

**InnerMirror** is not a conversation analyzer, not a chat summarizer, not an EQ grader.

It is a **mirror**.

Feed it a conversation — a meeting transcript, a chat log, a journal entry, a negotiation recap — and it won't judge or advise. It does one thing: **reflects back what you were actually doing in that field**.

> This is not mind-reading. This is closing the gap between what you think you were doing and what you were actually doing.

### Why

Humans are terrible at seeing themselves, not for lack of intelligence but because **the observer and the observed are the same person**. Every concession, assertion, deflection, interruption in a conversation is mostly unconscious — and by the time you recall it, you've already rationalized it.

Vipassanā meditation's core insight: **let a calm witness stand aside and watch**. The hard part is staying calm while being both witness and subject. AI has no such difficulty.

**InnerMirror** outsources the witness role to Claude. What you see isn't the AI's judgment — it's **what you were always doing but couldn't see**.

### Output

Feed a conversation in, get back:

- **Mental trajectory per speaker** — real motivations evolving, not just surface words
- **Signal map** — who sent what signals, what landed, what got ignored
- **Field diagnosis** — real power structure, emotional undertone, the unspoken line
- **Your position** — **the core** — the role you played vs. the role you thought you were playing

### Install

You'll need  any environment that supports Claude skills.

```bash
git clone https://github.com/zhujianneil/mirror.git ~/.claude/skills/neil-mirror
```

Then in Claude:
```
Use mirror to analyze this conversation: [paste]
```

### Best used for

- **10 minutes after an important meeting** — while memory is fresh
- **After a negotiation, interview, or date** — did you lead, or just think you did?
- **Conflict debriefs with family/partner** — behind every "I was just trying to..."
- **Your own internal dialogue** — journals, monologues, the back-and-forth of decisions

### Not for

- ❌ Psychological profiling of others (misuse)
- ❌ Real-time analysis during a conversation (you should be *in* it, not watching)
- ❌ Replacing real relationships, therapy, or meditation practice

---

## Philosophy

> 观身不净,观受是苦,观心无常,观法无我。
> *Contemplate the body as impure, feelings as suffering, mind as impermanent, phenomena as non-self.*
> — 四念处 · The Four Foundations of Mindfulness

The Buddha's vipassanā teaching points at four objects of observation. Modern life gives us a fifth: **the conversational field we live in every day**.

We rarely observe it because we're always inside it. This tool makes observation possible — imperfectly, through an external witness — but possible.

## License

MIT — use it, fork it, break it, improve it.
Just don't use it to judge other people. That's not what it's for.

---

## Author

**Neil (筑见)** · [zhujianneil.com](https://www.zhujianneil.com) · hi@zhujianneil.com

独立思想者 / FA财务顾问 · 价值投资 · AI 工作流 · 认知
*Independent thinker & advisor · Value investing · AI workflows · Cognition*

---

<div align="center">

*"搭骨架,看世界 · 照镜子,看自己"*
*Build the skeleton to see the world. Hold the mirror to see yourself.*

</div>
