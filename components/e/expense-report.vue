<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="re3nbbcdl"/><path class="n_5kpv26v"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:expense-report" /></template>
<style>
.n_5kpv26v {
  d: path("M8.5 3h7v4.5h-7Zm5.75 8c-.25-.85-1.1-1.25-2.25-1.25c-1.4 0-2.25.7-2.25 1.75c0 2.1 4.5 1.2 4.5 4c0 1-.95 1.75-2.25 1.75c-1.2 0-2.05-.5-2.25-1.25M12 8.25v1.5m0 7.5v1.5");
}

.re3nbbcdl {
  d: path("M8.5 5v-.5A1.5 1.5 0 0 1 10 3h4a1.5 1.5 0 0 1 1.5 1.5V5h2a2 2 0 0 1 2 2v12a2 2 0 0 1-2 2h-11a2 2 0 0 1-2-2V7a2 2 0 0 1 2-2Z");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
