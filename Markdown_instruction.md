#### **Инструкция для работы с Markdown**
### _Выделение текста_
Чтобы выделить текст курсивом необходимо обрамить его звездочками(*) или знаком нижнего подчеркивания(_). Например, *вот так* или _вот так_.

Чтобы выделить текст полужирным, необходимо обрамить его двойными звездочками(**) или двойным знаком нижнего подчеркивания(__). Например, **вот так** или __вот так__

Альтернативные способы выделения текста жирным или курсивом нужны для того, чтобы мы могли совмещать оба этих способа. Например, _текст может быть выделен курсивом и при этом быть **полужирным**_.
### _Списки_

Чтобы добавить ненумерованные списки, необходимо пункты выделить звездочкой(*) или знаком +. Например, вот так:
* Элемент 1
* Элемент 2
* Элемент 3
+ Элемент 4

Чтобы добавить нумерованные списки, необходимо пункты просто пронумеровать. Например, вот так:
1. Первый пункт
2. второй пункт
### _Работа с изображениями_
Чтобы вставить изображение в текст, достаточно написать следующее:

![цветочек](Chrysanthemum.jpg)
### _Ссылки_
### _Работа с таблицами_
### _работа с ветками_
Чтобы создать ветку необходима команда

**git branch [имя_ветки];**

чтобы удалить ветку:

**git branch -d [имя_ветки]**

Слияние веток:

**git merge [имя добавляемой ветки]**

Конфликт происходит при попытке внести изменения в разных ветках в одном и том же месте

### _Цитаты_
### _Заключение_

основные команды :

git init - создание репозитория в папке, из которой  мы  запускаем эту команду.

git add [имя файла] - добавляет файл в отслеживаемые.

git commit -m "обязательный комментарий"  - фиксирует состояние файла.

git diff - позволяет премещаться между зафиксированными состояниями.

git log - позволяет вывести список всех имеющихся коммитов.

git checkout - позволяет переходить между разными коммитами.
команда git log -graph отображает дерево коммитов
### _Git Hub_

git clon- копируем интересный репозиторий
git push -направляеь локальные изменения на сайт

