# Frontend Mentor - Testimonials grid section solution

## Languages
This first section is in English. 

[Versão em português logo abaixo.](#portuguese)

## Context

This is a solution to the [Testimonials grid section challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/testimonials-grid-section-Nnw6J7Un7). Frontend Mentor challenges help you improve your coding skills by building realistic projects. 

> Your challenge is to build out this testimonials grid section and get it looking as close to the design as possible.

## Table of contents

- [Overview](#overview)
  - [The challenge](#the-challenge)
  - [Screenshot](#screenshot)
  - [Links](#links)
- [My process](#my-process)
  - [Built with](#built-with)
  - [What I learned](#what-i-learned)
- [Author](#author)

## Overview

### The challenge

Users should be able to:

- View the optimal layout for the site depending on their device's screen size

### Screenshot

#### Desktop

<p align="center">
  <img src="./src/design/desktop-screenshot.png" alt="Desktop Screenshot of live page" title="Desktop Screenshot of live page" width="600px" />
</p>

#### Tablet

<p align="center">
  <img src="./src/design/tablet-screenshot.png" alt="Tablet proportions Screenshot of live page" title="Tablet proportions Screenshot of live page" width="450px" />
</p>

#### Mobile

<p align="center">
  <img src="./src/design/mobile-screenshot.jpg" alt="Mobile Screenshot of live page" title="Mobile Screenshot of live page" width="300px" />
</p>

### Links

- Solution URL: [GitHub Repository](https://github.com/xuaun/testimonials-grid-section)
- Live Site URL: [Live Page](https://xuaun.github.io/testimonials-grid-section/)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- CSS Grid
- Media Query

### What I learned

In this project I was able to use flexbox, grid, variable, and media query concepts in CSS, as well as using a ready-made Figma design to create this component. I also used `rem` for measurements and BEM methodology for naming classes.

```css
.testimonials {
  display: grid;
  grid-template:
    "big-horizontal-1 big-horizontal-1 small-1 big-vertical" auto
    "small-2 big-horizontal-2 big-horizontal-2 big-vertical" auto / 25.5rem 25.5rem 25.5rem 25.5rem;
  gap: 2.4rem 3rem;
}
```

## Author

- Website - [João Víctor de Araujo Lima's Portfolio](https://xuaun.github.io/)
- Frontend Mentor - [@xuaun](https://www.frontendmentor.io/profile/xuaun)


____
<br>

# <p id="portuguese">Frontend Mentor - Solução do projeto de seção de grid de depoimentos</p>

## Contexto

Esta é uma solução para o [desafio de seção de grid de depoimentos no Frontend Mentor](https://www.frontendmentor.io/challenges/testimonials-grid-section-Nnw6J7Un7). Os desafios do Frontend Mentor ajudam você a melhorar suas habilidades de codificação construindo projetos realistas.

> Seu desafio é criar essa seção de grid de depoimentos e fazer com que ela fique o mais próxima possível do design.

## Lista de conteúdos

- [Visão Geral](#visão-geral)
  - [Desafio](#desafio)
  - [Prints](#prints)
  - [Links](#links-pt)
- [Meu processo](#meu-processo)
  - [Tecnologias utilizadas](#tecnologias-utilizadas)
  - [O que eu aprendi](#o-que-eu-aprendi)
- [Autor](#autor)

## Visão Geral

### Desafio

Os usuários devem ser capazes de:

- Visualizar o layout ideal dependendo do tamanho da tela do dispositivo

### Prints

#### Computador

<p align="center">
  <img src="./src/design/desktop-screenshot.png" alt="Print da tela no Desktop" title="Print da tela no Desktop" width="600px" />
</p>

#### Tablet

<p align="center">
  <img src="./src/design/tablet-screenshot.png" alt="Print da tela nas proporções de um Tablet" title="Print da tela nas proporções de um Tablet" width="450px" />
</p>

#### Celular

<p align="center">
  <img src="./src/design/mobile-screenshot.jpg" alt="Print da tela no Celular" title="Print da tela no Celular" width="300px" />
</p>

### <p id="links-pt">Links</p>

- Link da solução: [Repositório no GitHub](https://github.com/xuaun/testimonials-grid-section)
- Site com a solução: [Página no ar](https://xuaun.github.io/testimonials-grid-section/)

## Meu processo

### Tecnologias utilizadas

- HTML5
- CSS
- Flexbox
- CSS Grid
- Media Query

### O que eu aprendi

Neste projeto eu pude utilizar conceitos de flexbox e grid, de variáveis e de media query no CSS, além de usar um design pronto do Figma para a elaboração deste componente. Eu também usei `rem` para medidas e metodologia BEM para nomear classes.

```css
.testimonials {
  display: grid;
  grid-template:
    "big-horizontal-1 big-horizontal-1 small-1 big-vertical" auto
    "small-2 big-horizontal-2 big-horizontal-2 big-vertical" auto / 25.5rem 25.5rem 25.5rem 25.5rem;
  gap: 2.4rem 3rem;
}
```

## Autor

- Website - [Portfólio - João Víctor de Araujo Lima](https://xuaun.github.io/)
- Frontend Mentor - [@xuaun](https://www.frontendmentor.io/profile/xuaun)

