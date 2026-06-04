<!DOCTYPE html>
<html lang="zh-CN">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0, maximum-scale=1.0">
<title>荣耀陪练 · 专业提升</title>
<style>
  @import url('https://fonts.googleapis.com/css2?family=Noto+Sans+SC:wght@300;400;500;700&display=swap');

  :root {
    --bg: #1a1a1e;
    --bg2: #242428;
    --bg3: #2e2e33;
    --card: #28282d;
    --accent: #f5c842;
    --accent2: #e6a800;
    --text: #f0f0f0;
    --text2: #a0a0a8;
    --text3: #606068;
    --green: #4cd964;
    --red: #ff3b30;
    --blue: #0a84ff;
    --border: #3a3a40;
    --radius: 14px;
    --radius-sm: 8px;
  }

  * { margin: 0; padding: 0; box-sizing: border-box; -webkit-tap-highlight-color: transparent; }

  body {
    font-family: 'Noto Sans SC', -apple-system, sans-serif;
    background: var(--bg);
    color: var(--text);
    min-height: 100vh;
    max-width: 430px;
    margin: 0 auto;
    position: relative;
    overflow-x: hidden;
  }

  .nav {
    position: fixed;
    bottom: 0; left: 50%; transform: translateX(-50%);
    width: 100%; max-width: 430px;
    background: rgba(28,28,32,0.96);
    backdrop-filter: blur(20px);
    border-top: 1px solid var(--border);
    display: flex;
    z-index: 100;
    padding-bottom: env(safe-area-inset-bottom);
  }
  .nav-item {
    flex: 1; display: flex; flex-direction: column;
    align-items: center; gap: 3px;
    padding: 10px 0;
    cursor: pointer; transition: all 0.2s;
    color: var(--text3);
    font-size: 11px;
  }
  .nav-item.active { color: var(--accent); }
  .nav-icon { font-size: 22px; line-height: 1; }

  .page { display: none; padding: 0 0 80px; animation: fadeIn 0.2s ease; }
  .page.active { display: block; }
  @keyframes fadeIn { from { opacity: 0; transform: translateY(6px); } to { opacity: 1; transform: translateY(0); } }

  .header {
    padding: 56px 20px 20px;
    background: var(--bg);
    position: sticky; top: 0; z-index: 50;
  }
  .header-row { display: flex; align-items: center; justify-content: space-between; }
  .header h1 { font-size: 22px; font-weight: 700; letter-spacing: -0.5px; }
  .header h1 span { color: var(--accent); }
  .badge { background: var(--accent); color: #000; font-size: 11px; font-weight: 700; padding: 3px 8px; border-radius: 20px; }

  .hero {
    margin: 0 16px 16px;
    background: linear-gradient(135deg, #2a2410 0%, #1e1a08 100%);
    border: 1px solid rgba(245,200,66,0.2);
    border-radius: var(--radius);
    padding: 20px;
    position: relative;
    overflow: hidden;
  }
  .hero::before {
    content: '⚔️';
    position: absolute; right: -10px; top: -10px;
    font-size: 80px; opacity: 0.08;
    transform: rotate(15deg);
  }
  .hero-tag { color: var(--accent); font-size: 11px; font-weight: 500; letter-spacing: 1px; margin-bottom: 6px; }
  .hero h2 { font-size: 20px; font-weight: 700; margin-bottom: 4px; }
  .hero p { color: var(--text2); font-size: 13px; line-height: 1.5; }
  .hero-stats { display: flex; gap: 20px; margin-top: 16px; }
  .stat { text-align: center; }
  .stat-num { font-size: 20px; font-weight: 700; color: var(--accent); }
  .stat-label { font-size: 11px; color: var(--text2); margin-top: 1px; }

  .section { padding: 0 16px; margin-bottom: 20px; }
  .section-title {
    font-size: 13px; font-weight: 500; color: var(--text2);
    margin-bottom: 10px; letter-spacing: 0.5px;
    display: flex; align-items: center; gap: 6px;
  }
  .section-title::after { content: ''; flex: 1; height: 1px; background: var(--border); }

  .service-grid { display: grid; grid-template-columns: 1fr 1fr; gap: 10px; }
  .service-card {
    background: var(--card);
    border: 1px solid var(--border);
    border-radius: var(--radius);
    padding: 16px;
    cursor: pointer;
    transition: all 0.2s;
    position: relative;
    overflow: hidden;
  }
  .service-card:active { transform: scale(0.97); }
  .service-card.selected { border-color: var(--accent); background: rgba(245,200,66,0.08); }
  .service-card.popular::before {
    content: '热门';
    position: absolute; top: 8px; right: 8px;
    background: var(--accent); color: #000;
    font-size: 10px; font-weight: 700;
    padding: 2px 6px; border-radius: 4px;
  }
  .service-icon { font-size: 28px; margin-bottom: 8px; }
  .service-name { font-size: 14px; font-weight: 600; margin-bottom: 4px; }
  .service-desc { font-size: 11px; color: var(--text2); margin-bottom: 8px; line-height: 1.4; }
  .service-price { font-size: 16px; font-weight: 700; color: var(--accent); }
  .service-price span { font-size: 11px; font-weight: 400; color: var(--text2); }

  .rank-list { display: flex; flex-direction: column; gap: 8px; }
  .rank-item {
    background: var(--card);
    border: 1px solid var(--border);
    border-radius: var(--radius-sm);
    padding: 14px 16px;
    display: flex; align-items: center; gap: 12px;
    cursor: pointer; transition: all 0.15s;
  }
  .rank-item:active { transform: scale(0.98); }
  .rank-item.selected { border-color: var(--accent); background: rgba(245,200,66,0.06); }
  .rank-emoji { font-size: 24px; width: 36px; text-align: center; }
  .rank-info { flex: 1; }
  .rank-name { font-size: 14px; font-weight: 600; }
  .rank-sub { font-size: 11px; color: var(--text2); margin-top: 2px; }
  .rank-price { font-size: 15px; font-weight: 700; color: var(--accent); }
  .rank-check { width: 20px; height: 20px; border-radius: 50%; border: 2px solid var(--border); display: flex; align-items: center; justify-content: center; font-size: 11px; }
  .rank-item.selected .rank-check { background: var(--accent); border-color: var(--accent); color: #000; }

  .input-group { margin-bottom: 12px; }
  .input-label { font-size: 12px; color: var(--text2); margin-bottom: 6px; display: block; }
  .input-field {
    width: 100%;
    background: var(--card);
    border: 1px solid var(--border);
    border-radius: var(--radius-sm);
    color: var(--text);
    font-size: 15px;
    font-family: inherit;
    padding: 13px 16px;
    outline: none;
    transition: border-color 0.2s;
  }
  .input-field:focus { border-color: var(--accent); }
  .input-field::placeholder { color: var(--text3); }

  .summary-card {
    background: var(--card);
    border: 1px solid var(--border);
    border-radius: var(--radius);
    padding: 16px;
    margin-bottom: 16px;
  }
  .summary-row {
    display: flex; justify-content: space-between; align-items: center;
    padding: 8px 0;
    border-bottom: 1px solid var(--border);
    font-size: 14px;
  }
  .summary-row:last-child { border-bottom: none; }
  .summary-row .label { color: var(--text2); }
  .summary-row .value { font-weight: 500; }
  .summary-total { font-size: 18px; font-weight: 700; color: var(--accent); }

  .btn {
    width: 100%;
    padding: 16px;
    border-radius: var(--radius);
    border: none;
    font-size: 16px;
    font-weight: 700;
    font-family: inherit;
    cursor: pointer;
    transition: all 0.2s;
  }
  .btn-primary { background: var(--accent); color: #000; }
  .btn-primary:active { background: var(--accent2); transform: scale(0.98); }
  .btn-secondary { background: var(--bg3); color: var(--text); margin-top: 10px; }

  .order-card {
    background: var(--card);
    border: 1px solid var(--border);
    border-radius: var(--radius);
    padding: 16px;
    margin-bottom: 10px;
  }
  .order-header { display: flex; justify-content: space-between; align-items: flex-start; margin-bottom: 10px; }
  .order-id { font-size: 11px; color: var(--text3); }
  .order-status { font-size: 11px; font-weight: 600; padding: 3px 8px; border-radius: 20px; }
  .status-pending { background: rgba(255,149,0,0.15); color: #ff9500; }
  .status-active { background: rgba(76,217,100,0.15); color: var(--green); }
  .status-done { background: rgba(160,160,168,0.15); color: var(--text2); }
  .order-game { font-size: 15px; font-weight: 600; margin-bottom: 4px; }
  .order-detail { font-size: 13px; color: var(--text2); margin-bottom: 12px; }
  .order-footer { display: flex; justify-content: space-between; align-items: center; }
  .order-price { font-size: 16px; font-weight: 700; color: var(--accent); }
  .order-time { font-size: 11px; color: var(--text3); }

  .profile-header {
    padding: 30px 20px 20px;
    display: flex; align-items: center; gap: 16px;
    background: var(--card);
    margin-bottom: 16px;
  }
  .avatar {
    width: 64px; height: 64px; border-radius: 50%;
    background: linear-gradient(135deg, var(--accent), var(--accent2));
    display: flex; align-items: center; justify-content: center;
    font-size: 28px;
  }
  .profile-name { font-size: 18px; font-weight: 700; margin-bottom: 4px; }
  .profile-rank { font-size: 13px; color: var(--accent); font-weight: 500; }
  .profile-stats { display: flex; background: var(--card); border-radius: var(--radius); margin: 0 16px 16px; overflow: hidden; border: 1px solid var(--border); }
  .profile-stat { flex: 1; text-align: center; padding: 16px 8px; border-right: 1px solid var(--border); }
  .profile-stat:last-child { border-right: none; }
  .profile-stat-num { font-size: 20px; font-weight: 700; color: var(--accent); }
  .profile-stat-label { font-size: 11px; color: var(--text2); margin-top: 2px; }

  .menu-list { margin: 0 16px; background: var(--card); border-radius: var(--radius); border: 1px solid var(--border); overflow: hidden; }
  .menu-item {
    display: flex; align-items: center; gap: 12px;
    padding: 16px;
    border-bottom: 1px solid var(--border);
    cursor: pointer; transition: background 0.15s;
    font-size: 14px;
  }
  .menu-item:last-child { border-bottom: none; }
  .menu-item:active { background: var(--bg3); }
  .menu-icon { font-size: 20px; width: 28px; text-align: center; }
  .menu-arrow { margin-left: auto; color: var(--text3); font-size: 16px; }

  .toast {
    position: fixed; top: 50%; left: 50%; transform: translate(-50%, -50%) scale(0.9);
    background: rgba(0,0,0,0.85); color: #fff;
    padding: 12px 24px; border-radius: 10px;
    font-size: 14px; z-index: 999;
    opacity: 0; pointer-events: none;
    transition: all 0.3s; backdrop-filter: blur(10px);
  }
  .toast.show { opacity: 1; transform: translate(-50%, -50%) scale(1); }

  .success-page {
    display: none; position: fixed; inset: 0;
    background: var(--bg); z-index: 200;
    flex-direction: column; align-items: center; justify-content: center;
    text-align: center; padding: 40px;
  }
  .success-page.show { display: flex; animation: fadeIn 0.3s ease; }
  .success-icon { font-size: 72px; margin-bottom: 20px; }
  .success-title { font-size: 24px; font-weight: 700; margin-bottom: 8px; }
  .success-sub { color: var(--text2); font-size: 14px; line-height: 1.6; margin-bottom: 32px; }
  .success-order { background: var(--card); border-radius: var(--radius); padding: 16px; width: 100%; margin-bottom: 24px; text-align: left; border: 1px solid var(--border); }
  .success-order-row { display: flex; justify-content: space-between; font-size: 13px; padding: 5px 0; }
  .success-order-row .l { color: var(--text2); }

  .review-card { background: var(--card); border: 1px solid var(--border); border-radius: var(--radius); padding: 14px; margin-bottom: 10px; }
  .review-header { display: flex; align-items: center; gap: 10px; margin-bottom: 8px; }
  .review-avatar { width: 32px; height: 32px; border-radius: 50%; background: var(--bg3); display: flex; align-items: center; justify-content: center; font-size: 16px; }
  .review-name { font-size: 13px; font-weight: 600; }
  .review-stars { color: var(--accent); font-size: 12px; margin-top: 1px; }
  .review-text { font-size: 13px; color: var(--text2); line-height: 1.5; }

  .chip { display: inline-block; background: var(--bg3); border: 1px solid var(--border); border-radius: 20px; padding: 4px 10px; font-size: 12px; color: var(--text2); margin: 3px; }
  .chip.active { background: rgba(245,200,66,0.12); border-color: var(--accent); color: var(--accent); }

  .notice { background: rgba(245,200,66,0.08); border: 1px solid rgba(245,200,66,0.2); border-radius: var(--radius-sm); padding: 12px 14px; font-size: 12px; color: var(--accent); line-height: 1.5; margin-bottom: 12px; }
</style>
</head>
<body>

<div class="page active" id="page-home">
  <div class="header">
    <div class="header-row">
      <h1>荣耀<span>陪练</span></h1>
      <span class="badge">在线预约</span>
    </div>
  </div>

  <div class="hero">
    <div class="hero-tag">⚡ 专业段位提升</div>
    <h2>王者荣耀陪练</h2>
    <p>一对一指导，快速突破瓶颈，越打越强</p>
    <div class="hero-stats">
      <div class="stat"><div class="stat-num">98%</div><div class="stat-label">好评率</div></div>
      <div class="stat"><div class="stat-num">1200+</div><div class="stat-label">服务学员</div></div>
      <div class="stat"><div class="stat-num">3年+</div><div class="stat-label">陪练经验</div></div>
    </div>
  </div>

  <div class="section">
    <div class="section-title">服务项目</div>
    <div class="service-grid">
      <div class="service-card popular selected" onclick="selectService(this,'段位提升','按段位计价')">
        <div class="service-icon">🏆</div>
        <div class="service-name">段位提升</div>
        <div class="service-desc">针对性陪练，稳定突破卡段</div>
        <div class="service-price">¥30 <span>起</span></div>
      </div>
      <div class="service-card" onclick="selectService(this,'单局陪练','¥15/局')">
        <div class="service-icon">⚔️</div>
        <div class="service-name">单局陪练</div>
        <div class="service-desc">单局体验，灵活预约</div>
        <div class="service-price">¥15 <span>/局</span></div>
      </div>
      <div class="service-card" onclick="selectService(this,'开黑组队','¥20/小时')">
        <div class="service-icon">🎮</div>
        <div class="service-name">开黑组队</div>
        <div class="service-desc">一起开黑，体验更好</div>
        <div class="service-price">¥20 <span>/小时</span></div>
      </div>
      <div class="service-card" onclick="selectService(this,'技术教学','¥25/小时')">
        <div class="service-icon">📈</div>
        <div class="service-name">技术教学</div>
        <div class="service-desc">复盘分析，快速进步</div>
        <div class="service-price">¥25 <span>/小时</span></div>
      </div>
    </div>
  </div>

  <div class="section">
    <div class="section-title">学员评价</div>
    <div class="review-card">
      <div class="review-header">
        <div class="review-avatar">🦊</div>
        <div><div class="review-name">温柔的狐狸</div><div class="review-stars">★★★★★</div></div>
      </div>
      <div class="review-text">跟着老师练了一周，从钻石打到星耀，思路清晰多了，强烈推荐！</div>
    </div>
    <div class="review-card">
      <div class="review-header">
        <div class="review-avatar">🐯</div>
        <div><div class="review-name">暴躁的老虎</div><div class="review-stars">★★★★★</div></div>
      </div>
      <div class="review-text">老师很耐心，会帮你分析每局失误，进步很快，值得！</div>
    </div>
  </div>
</div>

<!-- 预约页 -->
<div class="page" id="page-order">
  <div class="header">
    <div class="header-row"><h1>在线<span>预约</span></h1></div>
  </div>

  <div class="section">
    <div class="notice">📌 请如实选择当前段位，老师会根据你的情况制定提升方案</div>
    <div class="section-title">当前段位</div>
    <div class="rank-list">
      <div class="rank-item selected" onclick="selectRank(this,'青铜/白银','¥30')">
        <div class="rank-emoji">🥉</div>
        <div class="rank-info"><div class="rank-name">青铜 / 白银</div><div class="rank-sub">基础提升，建立正确思路</div></div>
        <div class="rank-price">¥30</div>
        <div class="rank-check">✓</div>
      </div>
      <div class="rank-item" onclick="selectRank(this,'黄金','¥50')">
        <div class="rank-emoji">🥇</div>
        <div class="rank-info"><div class="rank-name">黄金</div><div class="rank-sub">强化意识，突破瓶颈</div></div>
        <div class="rank-price">¥50</div>
        <div class="rank-check"></div>
      </div>
      <div class="rank-item" onclick="selectRank(this,'铂金','¥80')">
        <div class="rank-emoji">💎</div>
        <div class="rank-info"><div class="rank-name">铂金</div><div class="rank-sub">精细操作，提升节奏感</div></div>
        <div class="rank-price">¥80</div>
        <div class="rank-check"></div>
      </div>
      <div class="rank-item" onclick="selectRank(this,'钻石','¥120')">
        <div class="rank-emoji">🔷</div>
        <div class="rank-info"><div class="rank-name">钻石</div><div class="rank-sub">高端局思维，全面提升</div></div>
        <div class="rank-price">¥120</div>
        <div class="rank-check"></div>
      </div>
      <div class="rank-item" onclick="selectRank(this,'星耀','¥200')">
        <div class="rank-emoji">⭐</div>
        <div class="rank-info"><div class="rank-name">星耀</div><div class="rank-sub">顶端局专项训练</div></div>
        <div class="rank-price">¥200</div>
        <div class="rank-check"></div>
      </div>
    </div>
  </div>

  <div class="section">
    <div class="section-title">擅长位置</div>
    <div>
      <span class="chip active" onclick="toggleChip(this)">法师</span>
      <span class="chip" onclick="toggleChip(this)">射手</span>
      <span class="chip" onclick="toggleChip(this)">打野</span>
      <span class="chip" onclick="toggleChip(this)">辅助</span>
      <span class="chip" onclick="toggleChip(this)">坦克</span>
      <span class="chip" onclick="toggleChip(this)">刺客</span>
    </div>
  </div>

  <div class="section">
    <div class="section-title">预约信息</div>
    <div class="input-group">
      <label class="input-label">微信号（老师会添加你）</label>
      <input class="input-field" id="wechat" placeholder="请输入微信号" type="text">
    </div>
    <div class="input-group">
      <label class="input-label">游戏ID（选填）</label>
      <input class="input-field" id="gameid" placeholder="方便老师了解你的情况" type="text">
    </div>
    <div class="input-group">
      <label class="input-label">备注（选填）</label>
      <input class="input-field" id="remark" placeholder="如：想提升哪方面、方便的时间等" type="text">
    </div>
  </div>

  <div class="section">
    <div class="summary-card">
      <div class="summary-row"><span class="label">服务类型</span><span class="value" id="sum-service">段位提升</span></div>
      <div class="summary-row"><span class="label">当前段位</span><span class="value" id="sum-rank">青铜/白银</span></div>
      <div class="summary-row"><span class="label">预计费用</span><span class="value summary-total" id="sum-price">¥30</span></div>
    </div>
    <button class="btn btn-primary" onclick="submitOrder()">立即预约 · 老师30分钟内联系你</button>
    <button class="btn btn-secondary" onclick="showToast('请通过微信直接联系老师')">有疑问？联系客服</button>
  </div>
</div>

<!-- 订单页 -->
<div class="page" id="page-orders">
  <div class="header">
    <div class="header-row"><h1>我的<span>预约</span></h1></div>
  </div>
  <div class="section">
    <div class="order-card">
      <div class="order-header">
        <div class="order-id">订单 #20240601-001</div>
        <div class="order-status status-active">进行中</div>
      </div>
      <div class="order-game">⚔️ 段位提升</div>
      <div class="order-detail">钻石 → 星耀 · 法师位</div>
      <div class="order-footer">
        <div class="order-price">¥120</div>
        <div class="order-time">2小时前预约</div>
      </div>
    </div>
    <div class="order-card">
      <div class="order-header">
        <div class="order-id">订单 #20240530-008</div>
        <div class="order-status status-done">已完成</div>
      </div>
      <div class="order-game">🎮 开黑组队</div>
      <div class="order-detail">2小时 · 开黑3局</div>
      <div class="order-footer">
        <div class="order-price">¥40</div>
        <div class="order-time">3天前</div>
      </div>
    </div>
  </div>
</div>

<!-- 教练页 -->
<div class="page" id="page-profile">
  <div style="padding-top:56px"></div>
  <div class="profile-header">
    <div class="avatar">👑</div>
    <div>
      <div class="profile-name">荣耀教练</div>
      <div class="profile-rank">⭐ 最强王者 · 认证陪练</div>
    </div>
  </div>

  <div class="profile-stats">
    <div class="profile-stat"><div class="profile-stat-num">1.2k</div><div class="profile-stat-label">服务学员</div></div>
    <div class="profile-stat"><div class="profile-stat-num">98%</div><div class="profile-stat-label">好评率</div></div>
    <div class="profile-stat"><div class="profile-stat-num">3年</div><div class="profile-stat-label">陪练经验</div></div>
  </div>

  <div class="section">
    <div class="section-title">擅长英雄</div>
    <div>
      <span class="chip active">貂蝉</span>
      <span class="chip active">甄姬</span>
      <span class="chip active">诸葛亮</span>
      <span class="chip active">孙悟空</span>
      <span class="chip active">李白</span>
    </div>
  </div>

  <div class="menu-list">
    <div class="menu-item" onclick="showToast('微信：glory_coach')">
      <span class="menu-icon">💬</span> 联系教练
      <span class="menu-arrow">›</span>
    </div>
    <div class="menu-item" onclick="showToast('功能开发中')">
      <span class="menu-icon">🔔</span> 预约通知设置
      <span class="menu-arrow">›</span>
    </div>
    <div class="menu-item" onclick="showToast('功能开发中')">
      <span class="menu-icon">📊</span> 收入统计
      <span class="menu-arrow">›</span>
    </div>
    <div class="menu-item" onclick="showToast('感谢信任！')">
      <span class="menu-icon">⭐</span> 给教练评分
      <span class="menu-arrow">›</span>
    </div>
    <div class="menu-item" onclick="showToast('已复制分享链接')">
      <span class="menu-icon">📤</span> 分享给朋友
      <span class="menu-arrow">›</span>
    </div>
  </div>
</div>

<nav class="nav">
  <div class="nav-item active" onclick="switchPage('home',this)">
    <span class="nav-icon">🏠</span>首页
  </div>
  <div class="nav-item" onclick="switchPage('order',this)">
    <span class="nav-icon">📝</span>预约
  </div>
  <div class="nav-item" onclick="switchPage('orders',this)">
    <span class="nav-icon">📋</span>订单
  </div>
  <div class="nav-item" onclick="switchPage('profile',this)">
    <span class="nav-icon">👑</span>教练
  </div>
</nav>

<div class="toast" id="toast"></div>

<div class="success-page" id="success">
  <div class="success-icon">🎉</div>
  <div class="success-title">预约成功！</div>
  <div class="success-sub">教练会在30分钟内通过微信联系你<br>请保持微信在线</div>
  <div class="success-order" id="success-detail"></div>
  <button class="btn btn-primary" onclick="closeSuccess()">好的，等教练联系</button>
</div>

<script>
  let selectedRank = '青铜/白银';
  let selectedPrice = '¥30';
  let selectedService = '段位提升';

  function switchPage(name, el) {
    document.querySelectorAll('.page').forEach(p => p.classList.remove('active'));
    document.querySelectorAll('.nav-item').forEach(n => n.classList.remove('active'));
    document.getElementById('page-' + name).classList.add('active');
    el.classList.add('active');
  }

  function selectService(el, name, price) {
    document.querySelectorAll('.service-card').forEach(c => c.classList.remove('selected'));
    el.classList.add('selected');
    selectedService = name;
    document.getElementById('sum-service').textContent = name;
  }

  function selectRank(el, name, price) {
    document.querySelectorAll('.rank-item').forEach(r => {
      r.classList.remove('selected');
      r.querySelector('.rank-check').textContent = '';
    });
    el.classList.add('selected');
    el.querySelector('.rank-check').textContent = '✓';
    selectedRank = name;
    selectedPrice = price;
    document.getElementById('sum-rank').textContent = name;
    document.getElementById('sum-price').textContent = price;
  }

  function toggleChip(el) { el.classList.toggle('active'); }

  function submitOrder() {
    const wechat = document.getElementById('wechat').value.trim();
    if (!wechat) { showToast('请填写微信号'); return; }
    const orderNum = '#' + Date.now().toString().slice(-8);
    document.getElementById('success-detail').innerHTML = `
      <div class="success-order-row"><span class="l">订单编号</span><span>${orderNum}</span></div>
      <div class="success-order-row"><span class="l">服务类型</span><span>${selectedService}</span></div>
      <div class="success-order-row"><span class="l">当前段位</span><span>${selectedRank}</span></div>
      <div class="success-order-row"><span class="l">联系微信</span><span>${wechat}</span></div>
      <div class="success-order-row"><span class="l">费用</span><span style="color:var(--accent);font-weight:700">${selectedPrice}</span></div>
    `;
    document.getElementById('success').classList.add('show');
  }

  function closeSuccess() {
    document.getElementById('success').classList.remove('show');
    switchPage('orders', document.querySelectorAll('.nav-item')[2]);
  }

  function showToast(msg) {
    const t = document.getElementById('toast');
    t.textContent = msg;
    t.classList.add('show');
    setTimeout(() => t.classList.remove('show'), 2000);
  }
</script>
</body>
</html>
