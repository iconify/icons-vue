<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ux2u0rbkq"><circle class="c6vt1lbds"/><path class="ru0hrxb7l"/><path class="goa6xmsjx"/><path class="mgexl6bib"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:face-hold-tears-sharp" /></template>
<style>
.c6vt1lbds {
  cx: 12px;
  cy: 12px;
  r: 9.25px;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.goa6xmsjx {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M9 10.25h.01m5.99 0h.01");
}

.mgexl6bib {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m7.5 12.25l1.5 1l1.5-1m3 0l1.5 1l1.5-1m-7.25 4l1.35.9h2.8l1.35-.9");
}

.ru0hrxb7l {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m7.25 8l2.5-1m7 1l-2.5-1");
}

.ux2u0rbkq {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
}

</style>
