# 翁家翌：OpenAI，GPT，强化学习，Infra，后训练 | WhynotTV Podcast #4

> B站视频：https://www.bilibili.com/video/BV1darmBcE4A/
> 转录时间：2026-02-27
> 转录方式：yt-dlp + OpenAI Whisper API（whisper-1）
> 原始音频：95MB，2小时2分钟，分5块转录，共36,822字符

---

## 👶 早年经历
- 从小搞奥数，"System 1反应"做题，但学新东西比别人慢2-3倍——靠提前学弥补
- 初二自学完高中数学，初三开始微积分；动力是**"投资未来"**，非父母要求
- 高中OI竞赛：福建省队倒数第一，没拿金牌保送，靠高考降60分进清华

## 🎓 清华
- **最著名的事：把所有作业全部开源**——打破信息差，"现在清华CS新生认识我的比认识捐楼的还多"
- GPA策略：最低投入够用就行，"87分B+很满足，多一分时间都不想花"
- 误打误撞选了RL（以为是GAN），后发现是打游戏的，但坚持下去了
- 大四做出**天授（Tianshou）RL框架**：两周一人手撸，推倒RAOlib重来，核心是consistency

## 🌏 CMU + 疫情期间
- 疫情在家做了**退学online（tuixue）**签证查询系统，点击量过百万
- 两个项目都是"慈善"——有需求，自己做，开源，不为钱
- 申请工作：投18家只拿到Google和翁方（DeepSeek前身），最终选了OpenAI

## 🤖 加入OpenAI（2022年）
- John Schulman招的他——理由是**"github非常漂亮"**，面试题他2小时做完（共给3小时）
- 该面试题只测过两人：翁家翌和Andre（现Codex负责人），**通过率100%**
- 加入时ChatGPT还不是主线，只有John组在做WebGPT的后续版本

## ⚙️ 核心贡献：Post-Training RL Infra
- 搭建了**整个OpenAI post-training的RL Infra**，所以从GPT-3.5到GPT-5每个release都有他名字
- RLHF最大挑战：**不知道怎么评估模型好坏**——reward hacking导致分数涨上去再掉下来；最终靠人类评估解决
- 工业级RL Infra vs toy RL：toy环境简单模型简单；工业级模型巨大环境（prompt）极简，瓶颈全在inference/training效率
- **曾因连续高强度工作进了ER**，一周7天全天写code，后来养成每周两次跑3000米习惯

## 💡 核心观点

### Infra > Research
> "教一个researcher如何做好engineering，要远比教一个engineer如何做好research来得难"

### Bug决定模型好坏
> "每家infra都有不同程度的bug，谁修的bug越多，谁的模型就越好"——这也可能是Llama追不上GPT的原因

### 还没到AGI
> 现有pretrain+post-train路线，他认为还没到AGI——他个人标准是：能完成80-90%他认为有意义的task。目前连改他的infra代码都不放心

### DeepSeek的真正警示
> OpenAI不care哪个model刷榜第一，真正让他们警觉的是：**DeepSeek的内部迭代速度很快**，说明Infra做得好

### PhD vs 工业界
> 如果目标是AI lab，直接进工业界，读PhD是"浪费生命"——AI lab最需要的是Infra工程师，不是有paper的researcher

### OpenAI现在的挑战
> 3000人规模后context sharing inconsistency是核心问题，正在重构下一代Infra。他们在乎的是"单位时间内正确迭代次数"，不是榜单名次

### Sam Altman被开除内幕
> "就是不信任，董事会投票。底下干活的人非常shocked"——Sam最终留下是因为商业、融资、地缘政治这些事没他不行

### 宿命论
> 个人信奉确定性宇宙观——"所有事从宇宙大爆炸那刻就定好了"；同时接受"所以我只能忘掉这件事去体验人生"

---

## 时间戳索引
| 时间 | 话题 |
|------|------|
| 2:33 | 童年经历 |
| 8:10 | 高中OI竞赛 |
| 16:02 | 清华开源作业 |
| 19:23 | 与强化学习结缘 |
| 41:08 | 天授Tianshou框架 |
| 48:07 | tuixue退学online |
| 56:21 | CMU读研与加入OpenAI |
| 59:46 | 和John Schulman的面试 |
| 63:16 | 为什么没读PhD |
| 66:31 | Infra的重要性 |
| 73:13 | 什么是强化学习和Post-training |
| 84:09 | GPT RLHF前世今生 |
| 87:01 | 工业级RL Infra挑战 |
| 92:08 | 未来5-10年挑战 |
| 96:30 | 现有路线能否达到AGI |
| 104:02 | Sam Altman被开除内部视角 |
| 112:48 | 未来与宿命论 |
| 118:35 | 考虑过创业吗 |
