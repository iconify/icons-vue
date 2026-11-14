<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="kalqj6zxv"/><path class="aj5miu9io"/><path class="shrm2vb9w"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:cash-stack" /></template>
<style>
.aj5miu9io {
  d: path("M8 13.75a2.5 1.75 0 1 0 5 0a2.5 1.75 0 1 0-5 0Z");
}

.kalqj6zxv {
  d: path("M2.5 9.25h16v9h-16Z");
}

.shrm2vb9w {
  d: path("M5.5 9.25v-2A1.5 1.5 0 0 1 7 5.75h13a1.5 1.5 0 0 1 1.5 1.5v6a1.5 1.5 0 0 1-1.5 1.5h-1.5");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
