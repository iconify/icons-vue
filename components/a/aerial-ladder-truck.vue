<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="e2br2yjzw"/><path class="doi32dbsb"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:aerial-ladder-truck" /></template>
<style>
.doi32dbsb {
  d: path("M5 19.5a2 2 0 1 0 4 0a2 2 0 1 0-4 0Zm10.5 0a2 2 0 1 0 4 0a2 2 0 1 0-4 0Zm-12-10l13-6.5M5 12l13-6.5m-10.5 2L9 10m3.5-5L14 7.5");
}

.e2br2yjzw {
  d: path("M2.5 17.5V12h12V9.5H18l3.5 4v4Z");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
