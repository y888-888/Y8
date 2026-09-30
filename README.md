# KS للطباعة والإعلان — ملفات الموقع الكاملة

هذا الملف يحتوي على كود الموقع، الصور، الشعار، وملفات الإعداد اللازمة.

## التشغيل محلياً

1. ثبّت Node.js و pnpm.
2. من داخل مجلد المشروع شغّل:

```bash
pnpm install
PORT=5173 BASE_PATH=/ pnpm --filter @workspace/ks-printing-ads run dev
```

3. افتح الرابط الذي يظهره Vite في المتصفح.

## إنشاء نسخة الإنتاج

```bash
pnpm --filter @workspace/ks-printing-ads run build
```

الصفحة تعمل بتصميم عربي RTL، وتحتوي على الصور داخل مجلد `attached_assets`.
