<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="znm1y2b4o"/><path class="awthynk6v"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:ice" /></template>
<style>
.awthynk6v {
  d: path("M3 7.5h13.5L21 3m-4.5 4.5V21M6.25 15v-2.25a2 2 0 0 1 2-2");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.znm1y2b4o {
  d: path("M3 7.5L7.5 3H21v13.5L16.5 21H3Z");
}

</style>
