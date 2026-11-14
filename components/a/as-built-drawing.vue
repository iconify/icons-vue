<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="xe7-y6b0a"/><path class="xyl1y3a9j"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:as-built-drawing" /></template>
<style>
.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.xe7-y6b0a {
  d: path("M13.3 20.5H3v-18h16v11.3");
}

.xyl1y3a9j {
  d: path("M6.5 9.5v-4h9V14h-9v-1.5M11 14v-4m3.75 8l2 2L21 15.75");
}

</style>
