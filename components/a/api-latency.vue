<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="o2zzotkrd"/><path class="u4uj5eb1y"/><path class="a6k62accz"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:api-latency" /></template>
<style>
.a6k62accz {
  d: path("M18 16.5V18l1.25 1");
}

.o2zzotkrd {
  d: path("M11.95 17.895L10 19l-7.5-4.25v-8.5L10 2l7.5 4.25v5.68");
}

.u4uj5eb1y {
  d: path("M2.5 6.25L10 10.5l7.5-4.25M10 10.5V19m4.75-1a3.25 3.25 0 1 0 6.5 0a3.25 3.25 0 1 0-6.5 0Z");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
