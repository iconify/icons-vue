<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rm9aiibeh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:candle-taper" /></template>
<style>
.rm9aiibeh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M12 8.5za1.5 1.5 0 0 1 1.5 1.5v5.5A1.5 1.5 0 0 1 12 17a1.5 1.5 0 0 1-1.5-1.5V10A1.5 1.5 0 0 1 12 8.5M10 17h4a1 1 0 0 1 1 1a1 1 0 0 1-1 1h-4a1 1 0 0 1-1-1a1 1 0 0 1 1-1m2 2v2m-5 0h10M12 5.75C10.85 5 10.75 3.6 12 2c1.25 1.6 1.15 3 0 3.75");
}

</style>
