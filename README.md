<!-- LOCAL DRAFT: verify the APK, replace size/SHA placeholders, and publish the release before updating this README. -->
# DeenStep / ДинСтеп — Android test builds

[Русский](#русский) · [English](#english)

## Русский

DeenStep помогает постепенно приучаться к ходьбе и учиться небольшими шагами. Здесь доступны тестовые APK для Android.

**Тестовая версия 0.14.0.** [Скачать APK для Android](https://github.com/yssjf28dxj-cmyk/deenstep-releases/releases/download/v0.14.0/DeenStep-Test-0.14.0.apk) · [Описание версии](https://github.com/yssjf28dxj-cmyk/deenstep-releases/releases/tag/v0.14.0).

### Что изменилось в 0.14.0

- В настройках появилась **«Обратная связь»** с вариантами «Добавить / Изменить / Убрать / Ошибка». Черновик сохраняется на устройстве. Для отправки разработчику нажми «Отправить»; без связи сообщение можно отправить повторно позже. Профиль автоматически не прикладывается.
- Добавлена добровольная настройка **«Помогать улучшать приложение»**. Она **выключена по умолчанию**. Если включить её, разработчик получает версию приложения, дневные суммарные время и посещения пяти основных разделов — «Ходьба», «Учёба», «Привычки», «Истории», «Мой путь» — и отдельный технический идентификатор. Не передаются имя, вес, другие данные о здоровье, религиозные настройки, местоположение или тексты экранов. Демонстрация и браузерный просмотр не учитываются.
- Настройку можно выключить в любое время. Отправка прекращается; неотправленные данные статистики и её локальный идентификатор удаляются. Уже отправленные данные этим действием не удаляются.
- В отдельной демонстрации исправлен переход от вступления на 6-м дне к Алифу на 7-м. Настоящий профиль и прогресс сохраняются. Демонстрация использует тот же способ отрисовки, что и основной экран приложения.

В настройках также доступны локальный технический отчёт TXT и кнопка «Проверить вибрацию». Технические отчёты автоматически не отправляются. Проверка вибрации не меняет прогулку.

### Как скачать и установить

1. Открой раздел [Releases](https://github.com/yssjf28dxj-cmyk/deenstep-releases/releases) на Android-устройстве и выбери версию.
2. В разделе Assets скачай `DeenStep-Test-0.14.0.apk`. Архивы «Source code» не являются приложением.
3. Открой скачанный APK. Если Android попросит, разреши установку из используемого браузера или приложения «Файлы».
4. Подтверди установку в системном окне Android.

Для скачивания публичного APK не нужны аккаунты Google/GitHub или персональное приглашение.

**Если DeenStep уже установлен, устанавливай новую версию поверх прежней и выбирай «Обновить». Не удаляй приложение и не очищай его данные.** Перед обновлением можно дополнительно создать резервную копию в приложении. Если Android не предлагает обновление или сообщает о конфликте, сохрани точное сообщение и передай разработчику.

### Совместимость и ограничения

- Android 7.0 и новее. Датчики и вибрация зависят от устройства.
- Это тестовая сборка: возможны ошибки.
- Приёмочные проверки точности шагомера и ощущения вибрации на физических телефонах отложены.
- Этот APK предназначен для Android. Версии для iPhone/iPad пока нет.

## English

DeenStep helps you build a walking habit gradually and learn in small steps. This repository provides Android test APK downloads.

**Test version 0.14.0.** [Download the Android APK](https://github.com/yssjf28dxj-cmyk/deenstep-releases/releases/download/v0.14.0/DeenStep-Test-0.14.0.apk) · [Release notes](https://github.com/yssjf28dxj-cmyk/deenstep-releases/releases/tag/v0.14.0).

### What changed in 0.14.0

- Settings now include **Feedback** with Add / Change / Remove / Bug categories. Drafts stay on the device. Tap Send to send a message to the developer; if you are offline, you can retry later. Your profile is not automatically attached.
- **Help improve the app** is optional and **off by default**. When enabled, it shares the app version, daily totals for active time and visits to five main sections — Walk, Learn, Habits, Stories and My Path — plus a separate technical identifier. It does not share your name, weight, other health data, religious preferences, location or screen text. Demonstration and browser preview activity are excluded.
- You can turn this off at any time. Sending stops, and unsent usage statistics and their local identifier are cleared. This does not delete data already sent.
- The separate demonstration now carries the day 6 introduction forward to the Alif lesson on day 7. Your personal profile and progress stay saved. The demonstration uses the same rendering mode as the main app screen.

Settings also include a local technical TXT report and a Test vibration button. Technical reports are not sent automatically. The vibration test does not change your walk.

### Download and install

1. Open [Releases](https://github.com/yssjf28dxj-cmyk/deenstep-releases/releases) on your Android device and choose the version.
2. Under Assets, download `DeenStep-Test-0.14.0.apk`. “Source code” archives are not the app.
3. Open the downloaded APK. If Android asks, allow installation from the browser or Files app you are using.
4. Confirm installation in the Android system dialog.

Downloading the public APK does not require a Google account, a GitHub account or a personal invitation.

**If DeenStep is already installed, install the new version over it and choose Update. Keep the existing app installed and retain its data.** You can create an in-app backup before updating. If Android does not offer an update or reports a conflict, send the exact message to the developer.

### Compatibility and limitations

- Android 7.0 or later. Sensor and vibration behavior depends on the device.
- This is a test build and may contain bugs.
- Physical-phone acceptance checks for pedometer accuracy and felt vibration are deferred.
- This APK is for Android. An iPhone/iPad version is not available yet.

## APK details / Сведения об APK

| Field / Поле | Value / Значение |
| --- | --- |
| File / Файл | `DeenStep-Test-0.14.0.apk` |
| Version name | `0.14.0-dev` |
| Version code | `32` |
| Application ID | `app.shag.walking_app.dev` |
| Minimum Android | `7.0 (API 24)` |
| Size / Размер | `54632305` |

SHA-256:

```text
e1dea59ea77208ab355b2ff79622407b0a75b347572084bbc9c9a300b9d738bc
```

This repository contains public release information and Android binaries. App source code is maintained separately. Signing keys, user databases, feedback messages and usage statistics are not published here.

Репозиторий содержит открытую информацию о версиях и Android-сборки. Исходники приложения хранятся отдельно. Ключи подписи, базы пользователей, сообщения обратной связи и статистика использования здесь не публикуются.
