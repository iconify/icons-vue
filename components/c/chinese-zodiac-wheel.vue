<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="ivt66egxw"/><path class="yl_auqhjo"/><path class="y0_0t3rdq"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:chinese-zodiac-wheel" /></template>
<style>
.ivt66egxw {
  d: path("M2.5 12a9.5 9.5 0 1 0 19 0a9.5 9.5 0 1 0-19 0ZM12 2.5v19M2.5 12h19");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.y0_0t3rdq {
  d: path("M10.25 2h3.5L12 4.5Z");
}

.yl_auqhjo {
  fill: currentColor;
  d: path("M14 10V5.75A6.5 6.5 0 0 1 18.25 10Z");
}

</style>
