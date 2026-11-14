<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="ra-w1rhwh"/><path class="wgdalebrk"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:bath-running" /></template>
<style>
.ra-w1rhwh {
  d: path("M3 11h18v3a5 5 0 0 1-5 5H8a5 5 0 0 1-5-5Zm2.5 0V4.5a2 2 0 0 1 4 0v1m0 2.75V11");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.wgdalebrk {
  d: path("M7 15q2.5-1.5 5 0t5 0");
}

</style>
