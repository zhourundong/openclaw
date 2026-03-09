# MEMORY.md - 永久核心知识

---

## 🔒 硬规则 (CRITICAL)

> 同一类错误出现3次自动升级为此处规则

### 暂无硬规则

---

## 用户偏好
- **语言**: 中文
- **时区**: Asia/Shanghai
- **模型**: baiduqianfancodingplan/qianfan-code-latest
- **兴趣爱好**: 喜欢刷小红书

## 技能安装方式 (Critical)
- **优先方式**: GitHub 克隆方式安装 skill
- **原因**: ClawHub API 有速率限制
- **流程**: 
  1. 在 GitHub 搜索 skill 仓库
  2. 克隆到临时目录
  3. 复制到 /root/.openclaw/skills/ 或 /root/.openclaw/workspace/skills/
  4. 运行 openclaw skills check 验证
  5. 清理临时文件

### ClawHub 直接下载方式 (备选)
当 `clawhub install` 失败时，可使用：
1. 访问 https://clawhub.ai/ 搜索技能
2. 使用下载链接获取技能包：
   `https://wry-manatee-359.convex.site/api/v1/download?slug=<技能名>`
3. 下载并解压到全局技能目录：
   - `/root/.openclaw/skills/` (全局)
   - `/root/.openclaw/workspace/skills/` (工作区)

## 已安装的 Skills
- file-manager ✅
- skill-vetter ✅
- slide-creator ✅
- GitHub CLI (gh) ✅ - github skill 已就绪
- skill-cortex ✅ - 能力进化系统
- 招聘专员 ✅ - Agent 创建与管理专家

## 飞书配置
- **App ID**: cli_a92643b35779dbd3
- **Bot 名称**: 小龙虾
- **权限问题**: 缺少 contact:contact.base:readonly (仅影响发送者名称显示)

## 系统信息
- **主机**: iZwz90cv2e6tsi5kln13xpZ
- **操作系统**: Linux 6.8.0-100-generic (x64)
- **Node 版本**: v22.22.1
- **OpenClaw 版本**: 2026.2.24 (可更新: 2026.3.7)
- **Gateway 端口**: 18789

## 重要决定
- [2026-03-08] 使用 GitHub 克隆方式安装 skill，避免 ClawHub API 限制
- [2026-03-08] 安装了 SIAS Self-Improving Agent System
- [2026-03-08] 创建招聘专员 Agent，负责 Agent 创建与群聊绑定

## 定时任务 (Cron Jobs)
- 暂无活跃的定时任务

## GitHub 记忆同步
- **仓库**: https://github.com/zhourundong/openclaw
- **同步脚本**: `~/.openclaw/workspace/scripts/sync-memory.sh`
- **目录结构**:
  - `MEMORY.md` - 长期核心知识
  - `daily/YYYY-MM-DD/` - 每日工作记录

## Agent 群聊绑定
- **招聘专员**: 绑定到群聊 `oc_11f4c0e9ae12c5a0be6bbe38a1811a19`
  - 功能: 帮助创建各种 Agent 并绑定群聊
  - 风格: 大哥大风格，雷厉风行

## SOUL.md 规则 (简版)
1. WAL 协议: 回答前先保存，再回答
2. 错误立即记录到 .learnings/ERRORS.md
3. 任务开始/结束/决定时更新 SESSION-STATE.md
4. 每 10-15 次交互进行反思
5. 沟通: 直接、清晰、无废话

---

*最后更新: 2026-03-08*
