# 佔位圖清單

目前網站所有圖片皆以 `.img-placeholder`（品牌色調漸層色塊）代替，HTML 中皆以 `<!-- TODO -->` 註解標註對應 slot 與建議尺寸。正式素材到位後，請依下表將對應區塊改為 `<img>` 標籤（記得補上有意義的 `alt` 文案）。

## 首頁 index.html
| Slot | 說明 | 建議尺寸 |
|---|---|---|
| home-hero | Hero 背景，灰泥肌理特寫 | 2400×1600 |
| home-about-teaser | 品牌故事引導區工作室照 | 1400×1000 |

## 服務與工藝 services.html
| Slot | 說明 | 建議尺寸 |
|---|---|---|
| services-microcement | 微水泥工藝圖 | 1400×1750 |
| services-texture | 肌理藝術漆工藝圖 | 1400×1750 |
| services-metallic | 金屬珠光系列工藝圖 | 1400×1750 |
| services-swatch-01~08 | 材質色板小樣 | 600×600 |

## 目前使用的漆面示意圖（assets/images/reference/）
來源為 Topciment 官網（topciment.com）的微水泥實景圖，僅作背景與漆面示意，**不是塔芙完成案例**。取得自有拍攝素材後請替換：
- hero-microcement-living.webp — 首頁 Hero 背景（slot: home-hero）
- finish-microcement-dining.webp — 首頁「微水泥」服務卡片
- finish-microcement-bath.webp — 服務頁「微水泥」工藝圖（slot: services-microcement）
- finish-texture-kebana.jpg — 服務頁「肌理藝術漆」（來源：decorativikebana.it Decor，代理品牌素材，slot: services-texture）
- finish-metallic-kebana.jpg — 服務頁「金屬珠光」（來源：decorativikebana.it Metal，代理品牌素材，slot: services-metallic）

## 關於我們 about.html
| Slot | 說明 | 建議尺寸 |
|---|---|---|
| about-story | 品牌故事圖 | 1400×1750 |
| about-crew-01~03 | 工班施作／手作工序／調色試樣照 | 1600×2000 |
| about-studio-01~03 | 工作室環境圖 | 1600×2000 |

## 聯繫我們 contact.html
| Slot | 說明 | 建議尺寸 |
|---|---|---|
| contact-line-qr | Line 官方帳號 QR Code | 400×400 |

## Logo / Favicon
- `assets/images/logo/tough-logo.png`：官方 Logo（來自「業者logo.ai」，該檔內嵌的是點陣圖 3417×1066，非向量），已輸出為 1200px 寬透明底 PNG，用於導覽列與頁尾。
- `favicon.png`、`assets/images/logo/icon-192.png`、`icon-512.png`、`apple-touch-icon.png`：由 Logo 左側 TT 方塊裁切產生。
- `assets/images/logo/og-cover.jpg`：社群分享預覽圖（白底置中 Logo）。
- 若取得真正的向量版 Logo（SVG/EPS），可替換 `tough-logo.png` 以獲得更銳利的顯示。

## 待替換的品牌資訊（非圖片，一併列出方便檢查）
- 電話：目前為 `+886 2 1234 5678` 佔位，尚待提供實際電話
- ~~地址~~：已更新為「台南市永康區中華路727巷11號」
- Email：目前為 `hello@topciment.com` 佔位，尚待確認是否為實際 Email
- ~~Line 官方帳號連結~~：已更新為 `https://page.line.me/576iqumv`
- ~~Instagram~~：已更新為 `https://www.instagram.com/toughmaker`
- 小紅書：目前仍為 `#` 佔位，尚待提供實際連結
- ~~Google Maps 嵌入~~：已更新為工作室實際地址查詢
- Line QR Code 圖片：目前仍為佔位色塊，尚待提供實際 QR Code 圖檔
