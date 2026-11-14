<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="g6ulkabjn"/><path class="u50s7gb9m"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:element-dubnium" /></template>
<style>
.g6ulkabjn {
  d: path("M2.5 2.5h19v19h-19Z");
}

.u50s7gb9m {
  d: path("M5.5 11h2a3.5 3.5 0 0 1 0 7h-2Zm8.5 0v7m0-2.25a2.25 2.25 0 1 0 4.5 0a2.25 2.25 0 1 0-4.5 0M5.5 5.25V8m2.75-2.75a1 1.375 0 0 1 0 2.75a1 1.375 0 0 1 0-2.75m3.75 0h-1.5l-.25 1.25c1.25-.25 1.75.25 1.75.75c0 .75-1 1-1.75.5");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
