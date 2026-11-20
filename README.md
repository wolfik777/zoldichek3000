# zoldichek3000

Интерактивная страница Twitch-канала **zoldichek3000**.

## Структура проекта

- `index.html` — основной автономный файл сайта (анимации, сцена реки и льда, плеер Twitch, клипы, ссылки, донат).
- `assets/` — исходные медиафайлы проекта:
  - `hero-loop.webm` — зацикленная пинг-понг анимация персонажа на холме с прозрачным фоном (VP9 Alpha).
  - `hero.png` — портрет персонажа (резервный кадр).
  - `boat.png` — персонаж в деревянной лодке.
  - `chibi-schedule.webp`, `chibi-rules.webp`, `chibi-sheikhs.webp`, `chibi-socials.webp`, `chibi-donate.webp`, `art-lightning.webp` — иллюстрации и чиби-арты канала.
- `.github/workflows/deploy.yml` — автоматическая веб-публикация на GitHub Pages.

## Веб-публикация на GitHub Pages

1. Создай репозиторий на GitHub (например, `wolfik777/zoldichek3000`) и загрузи файлы проекта в ветку `main`.
2. Открой **Settings → Pages → Build and deployment → Source** и выбери **GitHub Actions**.
3. Workflow `Deploy to GitHub Pages` запустится автоматически и опубликует сайт по адресу `https://wolfik777.github.io/zoldichek3000/`.

## Автор

**wolfik777**
- GitHub: https://github.com/wolfik777
- Telegram: https://t.me/wolfik7777
