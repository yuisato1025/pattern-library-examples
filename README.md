# PATTERN LIBRARY EXAMPLES

## Motivation

When it comes to create design system for a product, I learned that you need a library of user interface (UI) patterns that designers and design teams use to build, and developers refer to it, which is called pattern library.
There are a few ways to create it, so I just want to make it clear that each approach"s pro and cons by comparing them.

## Screenshot

### 1. [ASTRUM](https://astrum.nodividestudio.com/)

<img width="1468" alt="スクリーンショット 2022-07-31 21 59 18" src="https://user-images.githubusercontent.com/58369263/182028185-eb936253-8442-4725-b56e-abb6754ca3cb.png">

- modern UI
- simple structure(.html & .md)
- simple configuration file(data.json)

### 2. [PatternLab](https://patternlab.io/)

<img width="1471" alt="image" src="https://user-images.githubusercontent.com/58369263/182019604-b84a1622-8596-4f6b-803b-e3c67cfb0e03.png">

- [handlebars](https://handlebarsjs.com/) or [twig](https://twig.symfony.com/) template engine can be selected
- responsive frame by default
- many directories separated for creating one component

### 3. [Fractal](https://fractal.build/)

<img width="1466" alt="image" src="https://user-images.githubusercontent.com/58369263/182020711-d6b037af-826d-418a-9ba2-e2e5f0ef965d.png">

- [handlebars](https://handlebarsjs.com/) template engine by default
- free to use any tempalte engines
- simple directories(components/docs)

## Check local

### Install Dependencies

```bash
$ yarn # in the root
```

### Start server

For astrum

```bash
$ yarn w astrum start # port 3001
```

For fractal
```bash
$ yarn w fractal start # port 3002
```

For fractal
```bash
$ yarn w pattern-lab start # port 3003
```
