<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="f18_f1p2j"/><path class="h7rf2jbtx"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:car-app" /></template>
<style>
.f18_f1p2j {
  d: path("M5.5 2.5h13v19h-13Z");
}

.h7rf2jbtx {
  d: path("M8.25 12a3.75 3.75 0 1 0 7.5 0a3.75 3.75 0 1 0-7.5 0Zm0 0h7.5M12 12v3.75");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
