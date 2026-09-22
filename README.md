# Aplikacja Multisystems

Projekt Flutter z automatycznym budowaniem Android APK przez GitHub Actions.

## Jak uruchomić build
1. Wgraj CAŁĄ zawartość tego folderu do głównego katalogu repozytorium `aplikacja_multisystems`.
2. Zrób commit do gałęzi `main`.
3. Otwórz zakładkę **Actions** w GitHub.
4. Workflow **Build Android APK** uruchomi się automatycznie.
5. Po zakończeniu otwórz wykonany workflow i pobierz artefakt **Multisystems-APK**. W środku będzie `app-release.apk`.

Workflow można też uruchomić ręcznie przez **Actions > Build Android APK > Run workflow**.

Uwaga: obecna aplikacja to baza projektu. Następnym krokiem może być przeniesienie funkcji istniejącej aplikacji Multisystems (klienci, urządzenia, serwisy, SMS, backup itd.) do Fluttera.
