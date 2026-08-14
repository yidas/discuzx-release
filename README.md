Discuz! X Release
=================

Discuz! PHP forum X series package release

---

## 升級版本節點

以下為Discuz升級的版本節點，版本升級範圍只能在每個節點區間內進行:

- X3.5 => X5.0
- X3.4 => X3.5
- X3.2 => X3.4
- X2.0 => X3.2
- 7.2 => X2.0

---

## 各版本環境支援

| Discuz!X 版本 | PHP 支援版本 | 資料庫 (DB) 支援版本 |
| :--- | :--- | :--- |
| **Discuz! X5.0** | PHP 8.0 ~ 8.3+ *(預設強制要求 8.0+)* | MySQL 5.7+ / 8.0+ / 8.4+ / 9.0+ <br> MariaDB 10.2+ *(全站 mandatory UTF-8/utf8mb4)* |
| **Discuz! X3.5** | PHP 5.6+ / 7.0+ / 8.0~8.2 | MySQL 5.5 ~ 8.0+ <br> MariaDB 10.2+ |
| **Discuz! X3.4** | PHP 5.3 ~ 7.4 *(後期社群補丁部分支援至 8.0)* | MySQL 5.1 ~ 5.7 / MariaDB 5.5 ~ 10.3 |
| **Discuz! X3.3** | PHP 5.3 ~ 7.2 | MySQL 5.1 ~ 5.6 |
| **Discuz! X3.2 及以下** | PHP 5.2 ~ 5.6 *(不支援 PHP 7+)* | MySQL 5.0 ~ 5.5 |


---

## 各版本安裝說明

### x3.5 => x5.0

```
- 確保您的舊版本 Discuz! 必須爲 X3.5 版本，如不滿足版本要求請先升級到此版本；
- 確保 UCenter 和 Discuz! 部署在一個數據庫中；
- 確保您已備份了數據庫和程式檔案，將舊版本程式檔案移動到其他目錄下；
- 將舊版本的配置檔案 config/config_global.php、config/config_ucenter.php 複製到當前新版本的 config/ 目錄中；
- 點擊“下一步”開始升級；
- 升級完成後可以將舊版本中 source/plugin/ 目錄下的插件檔案挑選後複製到新版本的對應目錄下、將 template/ 目錄下的模板檔案挑選後複製到新版本的對應目錄下（不要複製 t- emplate/default/ 目錄）；
- 升級完成後 data/attachment/ 目錄以及 data/ 目錄下其他目錄請酌情複製；如舊版本應用涉及其他目錄中的檔案，請自行諮詢相關開發者複製；
```

---

## 參考

[Discuz!版本歷史](https://zh.wikipedia.org/wiki/Discuz!#%E7%89%88%E6%9C%AC%E6%AD%B7%E5%8F%B2)
