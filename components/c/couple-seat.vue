<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="dk0hjh2db"/><path class="ymfg-abwj"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:couple-seat" /></template>
<style>
.dk0hjh2db {
  d: path("M2.5 10a1.5 1.5 0 0 1 3 0v4h5v-4a1.5 1.5 0 0 1 3 0v4h5v-4a1.5 1.5 0 0 1 3 0v8h-19Z");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.ymfg-abwj {
  d: path("M5.5 10V5.5A1.5 1.5 0 0 1 7 4h2a1.5 1.5 0 0 1 1.5 1.5V10m3 0V5.5A1.5 1.5 0 0 1 15 4h2a1.5 1.5 0 0 1 1.5 1.5V10M4 18v3m16-3v3");
}

</style>
