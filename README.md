# Кастомный видеоплеер
![max example](screenshots/player.gif)

Построен на базе библиотеки [Playable](https://wix.github.io/playable/).

- Файл плеера:
[index.html](./index.html)
Для просмотра файла откройте файл [index.html](./index.html) в рабочей директории или откройте [ссылку](https://wepeqoor1.github.io/video-player/) для просмотра готового примера.

Если хочется выбрать другое видео, с помощью аргумента `src` плееру можно указать какое видео проигрывать, ссылки обязаны заканчиваться расширением файла:

```html
<script type="text/javascript">
  createPlayer({
    elementId: 'player',
    src: 'https://dvmn.org/media/filer_public/d0/16/d016d9b8-4180-4bb9-ad83-0241f61627b8/samsung_demo_-_alive_in_color.mp4'
});
</script>
```
