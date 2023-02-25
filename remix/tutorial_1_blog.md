[<- Назад](../README.md)

# Remix. Урок 1. Блог.

*Оригинал урока смотри [по ссылке.](https://remix.run/docs/en/v1/tutorials/blog)*

### Необходимо для урока:
* [Node.js](https://nodejs.org/) версии ^14.17.0 или >=16.0.0
* [npm](https://www.npmjs.com/) версии 7 или выше

Создаем новый проект Remix. Назовем его `tutorial_1_blog`. Вы можете назвать по-другому:

```shell
npx create-remix@latest --template remix-run/indie-stack tutorial_1_blog
```

Во время создания проекта в терминале вы увидите вопрос: 

```shell
? Do you want me to run `npm install`?
```

Отвечаем на него - `Yes`.

О доступных стэках можно почитать в [документации по стекам.](stacks.md)

В этом уроке мы использовали [indie stack](https://github.com/remix-run/indie-stack).  
Этот стек представляет собой полнофункциональное веб приложение и он готов к развертыванию на сервисе [fly.io](https://fly.io/).

> Проект Remix можно создать просто командой `npx create-remix@latest` без использования шаблона, то есть без указания флага `--template` 

[<- Назад](../README.md)