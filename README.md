zhugela 👋

Java 后端开发（大三下）｜Spring Boot｜Redis｜MySQL｜Spring AI
主线：2 个已上线项目 + 刷八股 + 算法（把「会用」升级到「能讲清原理 + 能排错」）



🚀 我在做什么





🧩 项目主线：星图库 StarPicture（已上线）— 云图库 + 协作编辑 + AI 扩图 / 以图搜图



🤖 AI 应用线：AI 旅游规划助手 — Spring AI + RAG + ReAct + Tool Calling



🧠 八股训练：Java 基础 / 并发 / JVM / Spring / MySQL / Redis / 消息队列



🧪 算法维持：LeetCode（保持手感 + 形成可复述的解题模板）



⚡ 效率工具：Cursor 辅助开发（Prompt 模板、生成 / 解释 / Debug / 结构化总结）



🧰 技术栈





后端：Java 17/21、Spring Boot 3、Spring MVC、MyBatis-Plus、Sa-Token



数据库：MySQL（索引、分页、聚合统计）、ShardingSphere 动态分表



缓存 / 中间件：Redis、Caffeine 多级缓存、Redis Stream / RabbitMQ



存储 & 网络：腾讯云 COS（分片上传、断点续传、MD5 秒传）、HTTP / WebSocket



并发 & 架构：线程池、JUC、CompletableFuture、Disruptor 无锁队列



AI 应用：Spring AI、RAG、PGvector、ReAct、Tool Calling、MCP、Prompt Engineering



工程化：Git、Maven、Swagger、JUnit 5、Nginx + 宝塔部署、统一错误码



📌 项目精选

1）星图库 StarPicture（已上线）

在线体验： http://43.139.218.240/

智能协同云图库，支持公开 / 私有 / 团队三大图库。累计用户 320+，图片 8,000+ 张，核心读接口峰值 QPS 60+。

我负责 / 实现：





用户鉴权：MD5 + 盐值、Redis + Spring Session、Sa-Token RBAC



图片链路：COS 上传、MD5 秒传、分片上传 + 断点续传（成功率 99.2%）



性能优化：Redis + Caffeine 多级缓存（接口耗时 -40%）、ShardingSphere 动态分表



批量处理：CompletableFuture + Jsoup 批量导图（效率 +300%）



实时协作：WebSocket 编辑锁 + Disruptor 异步消息处理



AI 集成：阿里云百炼异步扩图；以图搜图 Top-3 命中率 86%



部署上线：宝塔 + Nginx（反向代理、静态加速、访问控制）



关键词：COS、多级缓存、分表、WebSocket、Disruptor、异步 AI 任务、已上线



2）AI 旅游规划助手

基于 Spring Boot 3 + Spring AI 的智能行程规划，支持多轮对话、记忆持久化、RAG 检索与 ReAct 自主规划。

我负责 / 实现：





多模型接入：通义 / Ollama 统一 ChatClient 调用层，支持流式输出



RAG 优化：PGvector + Vector + BM25 混合检索 + Rerank（召回 92%）



对话记忆：Spring AI ChatMemory + Kryo 本地持久化，重启不丢上下文



智能体：ReAct 分解任务，Tool Calling 对接天气 / 地图 / 酒店 API



Prompt 工程：System Prompt + Few-shot 约束结构化行程输出



关键词：Spring AI、RAG、ReAct、Tool Calling、MCP、PGvector、Kryo



3）苍穹外卖（学习复盘）

Spring Boot 三层架构 + JWT + Redis 登录态 + 权限控制，用于夯实鉴权链路与异常治理。



关键词：JWT、拦截器、Redis Session、RBAC、可维护性



🧠 我在补齐的「面试高频能力」





HashMap 原理：数组 + 链表 + 红黑树；扩容；负载因子 0.75 的权衡



ConcurrentHashMap / 线程池：核心参数、拒绝策略、CompletableFuture 使用场景



JVM GC：常见回收算法与调优思路（能结合项目讲，而不是背名词）



Redis 缓存：穿透 / 击穿 / 雪崩；多级缓存一致性；分布式锁边界



MySQL：索引最左前缀、MVCC、分表分库路由（对照 ShardingSphere 源码）



Spring 工程细节：@Transactional 失效场景、CORS、Long 序列化、全局异常处理



AI 应用：RAG 流程、Embedding 检索、ReAct vs 普通 Chain、Tool Calling 设计



📚 我的学习方式（目前有效）





学完一块就做 「40 秒面试复述」：一句话 → 追问 → 生活例子 → 易错点



项目每修一个 bug 就写 「问题 - 原因 - 修复 - 收益」 笔记



算法不追数量：追 模板化表达（能清楚讲思路和复杂度）



项目题必绑源码：打开 StarPicture / ai-travel-planner 对照讲，避免「只背简历」



📈 近期目标





✅ 星图库上线 + AI 旅游助手核心链路打通



🔁 八股稳定：每天 10 题（输出笔记）+ 每周复盘



🧩 算法保温：每周 5 题（至少 2 题写总结）



🎯 实习投递：Java 后端实习，重点准备项目深挖 + AI 应用开发



📫 联系我





GitHub： https://github.com/zhugela



Email： zyuanliang971@gmail.com



Blog / Notes： CSDN、掘金、编程导航





我不追「看懂了」，我追 「能讲清 + 能写出来 + 能排错」。

