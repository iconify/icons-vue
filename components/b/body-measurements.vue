<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="p8c5hc5mp"/><path class="w2m9g1bou"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:body-measurements" /></template>
<style>
.p8c5hc5mp {
  d: path("M3.5 2.5h9a1 1 0 0 1 1 1v9a1 1 0 0 1-1 1h-9a1 1 0 0 1-1-1v-9a1 1 0 0 1 1-1Zm10 4.5c5.5 0 8 3.5 8 9v5.5h-4V20h1v-4c0-4-2-6-5-6");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.w2m9g1bou {
  d: path("M6 8a2 2 0 1 0 4 0a2 2 0 1 0-4 0Zm12.25 5.5h3.25m-3 3.5h3");
}

</style>
