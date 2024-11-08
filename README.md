# practicum-task
На платформе GitHub хранится множество проектов, часть из них находится в открытом доступе.
Процесс копирования удалённого репозитория на локальный компьютер называется клонированием.
Клонирование репозитория - обычно первое, что делает разработчик на новом месте работы.
Клонировать репозиторий - git clone.
Если вы не настраивали SSH-ключ, рекомендуем ещё раз заглянуть в урок об SSH и настроить его.
Команда git clone автоматически связывает локальный и удалённый репозитории.
Допустим, вы хотите усовершенствовать чужой проект или как-то использовать его в своей работе, но у вас нет прав на изменение оригинального репозитория.
Fork (англ. «развилка», «ответвление»), или «форк», - это GitHub-операция; напрямую с Git она не связана.
Основные команды для работы с git:
1. `git clone <repository-url>` - Клонировать репозиторий на локальный компьютер.
2. `git branch <branch-name>` - Создать новую ветку.
3. `git pull origin <branch-name>` - Получить последние изменения из удаленной ветки.
4. `git add <file-name>` или `git add .` - Добавить файлы в индекс для последующего коммита (точка добавляет все измененные файлы).
5. `git commit -m "commit message"` - Сделать коммит изменений с сообщением.
6. `git push origin <branch-name>` - Отправить изменения в удаленный репозиторий.
7. `git fetch` - Получить изменения из удаленного репозитория, не