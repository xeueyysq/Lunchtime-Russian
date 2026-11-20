# Lunchtime Cozy Create and Cooking по-русски

Неофициальный русификатор для **Lunchtime Cozy Create and Cooking 2.6.0**, Minecraft 1.20.1 и Forge.

- [Полный ресурс-пак — Lunchtime-Russian-Full-2.6.0.zip](https://github.com/xeueyysq/Lunchtime-Russian/releases/download/v2.6.0/Lunchtime-Russian-Full-2.6.0.zip) переводит тексты модов и добавляет русские страницы Patchouli для BetterEnd и Butchery.
- [Патч квестов и Мисо — Lunchtime-Russian-Quests-2.6.0.zip](https://github.com/xeueyysq/Lunchtime-Russian/releases/download/v2.6.0/Lunchtime-Russian-Quests-2.6.0.zip) переводит квестовую книгу Ember’s Questing и путеводитель Мисо.
- [Первоначальный ресурс-пак — Lunchtime-Russian-2.6.0.zip](https://github.com/xeueyysq/Lunchtime-Russian/releases/download/v2.6.0/Lunchtime-Russian-2.6.0.zip) доступен для тех, кто хочет сохранить прежний вариант.
- [Контрольные суммы SHA-256 новых ZIP](https://github.com/xeueyysq/Lunchtime-Russian/releases/download/v2.6.0/SHA256SUMS-full.txt) · [Страница релиза](https://github.com/xeueyysq/Lunchtime-Russian/releases/tag/v2.6.0) · [Оригинальная сборка](https://www.curseforge.com/minecraft/modpacks/lunchtime-cozy-create-cooking/files/9716665)

## Установка ресурс-пака

1. Откройте папку Minecraft профиля Lunchtime. В ней находятся `mods`, `config` и `resourcepacks`.
2. Положите полный ZIP в `resourcepacks`. Включайте один вариант русификатора Lunchtime за раз.
3. Выберите в игре **Русский (Россия)** и включите ресурс-пак. Если другие пакеты переопределяют те же строки, поднимите Lunchtime выше них в списке.

## Установка квестов и путеводителя Мисо

1. Закройте игру и распакуйте ZIP квестов в отдельную папку.
2. Откройте PowerShell 7 в этой папке и выполните команду, указав путь к папке Minecraft профиля.

```powershell
.\config-patch.ps1 -GameDirectory 'C:\путь\к\профилю\minecraft'
```

Добавьте `-VerifyOnly`, чтобы проверить совпадение исходных строк без записи. Скрипт заменяет совпавшие текстовые поля и сохраняет исходные файлы в папке `lunchtime-ru-backup-…` внутри профиля. Для отката скопируйте папку `config` из резервной копии поверх `config` профиля. На сервере могут использоваться собственные данные квестов.

Часть строк переведена локальной моделью и вычитана выборочно. Некоторые подписи Lunch Worlds зашиты в коде и остаются на английском. Установка проверена на копии файлов. Проверки в запущенной игре пока не было. Уведомления и лицензии использованных переводов сообщества находятся в `CREDITS.txt` внутри ресурс-пака.

## English installation summary

Download the [full resource pack](https://github.com/xeueyysq/Lunchtime-Russian/releases/download/v2.6.0/Lunchtime-Russian-Full-2.6.0.zip), place the ZIP in the Lunchtime instance’s `resourcepacks` folder, and enable it with **Russian (Russia)** selected. The [original resource pack](https://github.com/xeueyysq/Lunchtime-Russian/releases/download/v2.6.0/Lunchtime-Russian-2.6.0.zip) is still available.

For the quest book and Miso’s guide, close the game, extract the [quest patch](https://github.com/xeueyysq/Lunchtime-Russian/releases/download/v2.6.0/Lunchtime-Russian-Quests-2.6.0.zip), and run `config-patch.ps1` in PowerShell 7 with `-GameDirectory` pointing to the instance’s Minecraft folder. Add `-VerifyOnly` for a dry run. To restore the original files, copy `config` from the timestamped backup into the instance.
