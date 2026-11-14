<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="qbrr8ubfv"/><path class="mom_9hbqh"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:bin-compactor-solar" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.mom_9hbqh {
  d: path("M4.25 19.5a1.75 1.75 0 1 0 3.5 0a1.75 1.75 0 1 0-3.5 0m12.5-1.5a1.25 1.25 0 1 0 2.5 0a1.25 1.25 0 1 0-2.5 0M18 15v-1m0 7v1m-3-4h-1m7 0h1m-6.25-2.25L15 15m5.25.75L21 15m-5.25 5.25L15 21m5.25-.75L21 21");
}

.qbrr8ubfv {
  d: path("M2.75 3.25h11m-2.526 14.5H5L4 6h8.5l-.656 10.279");
}

</style>
