# Game-Life-
Учебный проект игра "Жизнь".

Учебный проект по освоению фрейморка Flask. Игра представляет собой клеточный автомат(https://ru.wikipedia.org/wiki/Клеточный_автомат). 
<p>На главной странице проэкта(index.html) можно задать размер поля клеточного автомата. Стороны поля не должны быть пустыми,
иначе будут применены параметры по умолчанию(размер поля 20 на 20 ячеек).</p>
![1](https://user-images.githubusercontent.com/92391770/144743326-8e93bacd-0f44-40b4-9ccd-199a2851740a.jpg)
<p>По нажатию кнопки "Создать жизнь" осуществляется переход на страницу "/live". Там в соответствии с игровой логикой генерируется мир в виде таблицы, ячейки которой, являются клетками. Зеленые клетки это - живые клетки, красные - клетки которые погибли, так же есть пустые клетки, в которых может зародится жизнь, если условия благоприятны.</p>
![1gif](https://user-images.githubusercontent.com/92391770/144744487-d8cedb58-a278-41ce-a844-675ffdc36d7d.gif)
<p>Для динамического обновления счётчика поколений и самой таблицы, используется библиотека jquery и технология ajax. 
Для счётчика поколений добавил отступ(margin-right: 400px;) в файле "style.css" класс ".counter" для того чтобы на некоторых разрешениях экрана, счётчик не был перекрыт кнопками.</p>
