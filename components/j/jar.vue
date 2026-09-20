<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":128,"height":128};
const content = `<path class="zkkmwubzy"/><ellipse class="dx3nbvbaw"/><path class="irib8qnpq"/><path class="o97j-0bud"/><path class="c99sgab8i"/><ellipse class="rirbtibvs"/><path class="fkj7g0b0w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noto:jar" /></template>
<style>
.c99sgab8i {
  fill: var(--svg-color--e2a610, #e2a610);
  d: path("M99.79 12.1H28.17s-.82 2.18-.77 5.9c.07 6.72 1.94 7.26 4.36 8.4c5.89 2.77 17.12 4.68 32.17 4.68s26.28-1.9 32.17-4.68c2.42-1.14 4.29-1.68 4.36-8.4c.04-3.72-.67-5.9-.67-5.9");
}

.dx3nbvbaw {
  cx: 64px;
  cy: 110.45px;
  fill: var(--svg-color--1492c4, #1492c4);
  opacity: var(--svg-opacity--0-6, 0.6);
  rx: 35.86px;
  ry: 8.47px;
}

.fkj7g0b0w {
  fill: var(--svg-color--ffe36c, #ffe36c);
  d: path("M40.94 20.94c5.35.65 6.23.65 6.72 2.27c.22.75.05 1.63-.53 2.14c-2.79 2.46-9.47 1.28-12.23-.8c-.98-.74-2.23-2.74-.71-4.09c1.43-1.26 4.5.21 6.75.48");
}

.irib8qnpq {
  fill: var(--svg-color--1492c4, #1492c4);
  d: path("m33.05 25.09l-3 4.03s18 13.26 52.75 7.91c19.58-3.01 14.68-8.85 14.68-8.85l-2.82-4.33z");
  opacity: var(--svg-opacity--0-6, 0.6);
}

.o97j-0bud {
  fill: var(--svg-color--fff, #fff);
  d: path("M40.99 91.6c.64 8.18-8.75 11.52-11.34 3.32c-.86-2.73-.43-5.67-.16-8.52c.65-6.69.49-13.45-.46-20.1c-.9-5.85-2.01-19.47 3.88-22.44c2.58-1.3 4.62-.67 6.57.32c2.85 1.66 3.18 5.58 3.1 8.87c-.15 5.66-.76 11.3-1.2 16.94c-.48 6.23-1.89 10.85-1.17 15.84c.27 1.92.69 3.85.78 5.77");
  opacity: var(--svg-opacity--0-8, 0.8);
}

.rirbtibvs {
  cx: 64px;
  cy: 12.47px;
  fill: var(--svg-color--9e740b, #9e740b);
  rx: 35.86px;
  ry: 8.47px;
}

.zkkmwubzy {
  fill: var(--svg-color--9fe1ea, #9fe1ea);
  d: path("M106.64 52.3c0-5.39-.1-9.76-2.52-14.7c-1.47-3.01-7.34-11.23-8.51-12.26H33.04c-1.17 1.03-7.04 9.25-8.51 12.26c-2.42 4.93-2.52 9.31-2.52 14.7c0 7.73.03 56.22-.01 57.05c-.11 2.72 1.83 4.85 4.93 6.84c9.95 6.38 28.64 7.81 37.39 7.81s27.44-1.43 37.39-7.81c3.11-1.99 5.04-4.12 4.93-6.84c-.03-.83 0-49.32 0-57.05");
  opacity: var(--svg-opacity--0-8, 0.8);
}

</style>
