<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="agwkgjb9z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:candle-chart-outline-regular" /></template>
<style>
.agwkgjb9z {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M5 10.5V13m-2 0h4v5H3Zm2 5v2.5m7 -14V9m-2 0h4v5h-4Zm2 5v2.5m7 -14V5m-2 0h4v5h-4Zm2 5v2.5");
}

</style>
