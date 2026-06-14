# Çevre-1 Güvenlik Raporu APK

## GitHub Actions ile APK Build

1. Bu klasörü GitHub'a yükle (yeni repo oluştur)
2. Actions sekmesine git
3. "Build Android APK" workflow otomatik başlar
4. Bittikten sonra Actions > ilgili run > Artifacts kısmından APK'yı indir

## Dosya Yapısı

```
cevre1-apk/
├── www/
│   └── index.html       ← Uygulama
├── capacitor.config.json
├── package.json
├── .github/
│   └── workflows/
│       └── build-apk.yml  ← APK build talimatı
└── README.md
```

## Özellikler
- Tüm veriler cihazda (localStorage) saklanır
- İnternet gerekmez
- Vardiya saatleri ayarlanabilir
- Park/alan listesi yönetilebilir
