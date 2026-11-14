<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="npk3-51bl"/><path class="bmnc-y6mj"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:camera-two-way-audio" /></template>
<style>
.bmnc-y6mj {
  d: path("M9 13a3 3 0 1 0 6 0a3 3 0 1 0-6 0Zm7.405-3.696a5.75 5.75 0 0 1 0 7.392m-8.81 0a5.75 5.75 0 0 1 0-7.392");
}

.npk3-51bl {
  d: path("M3 8.5a2 2 0 0 1 2-2h2.5L9 4h6l1.5 2.5H19a2 2 0 0 1 2 2V18a2 2 0 0 1-2 2H5a2 2 0 0 1-2-2Z");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
