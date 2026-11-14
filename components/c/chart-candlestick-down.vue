<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="cz51ix-6z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:chart-candlestick-down" /></template>
<style>
.cz51ix-6z {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M6 5za1.5 1.5 0 0 1 1.5 1.5v4A1.5 1.5 0 0 1 6 12a1.5 1.5 0 0 1-1.5-1.5v-4A1.5 1.5 0 0 1 6 5m6 3.5za1.5 1.5 0 0 1 1.5 1.5v3a1.5 1.5 0 0 1-1.5 1.5a1.5 1.5 0 0 1-1.5-1.5v-3A1.5 1.5 0 0 1 12 8.5m6 4za1.5 1.5 0 0 1 1.5 1.5v3a1.5 1.5 0 0 1-1.5 1.5a1.5 1.5 0 0 1-1.5-1.5v-3a1.5 1.5 0 0 1 1.5-1.5M6 2.5V5m0 7v2.5M12 6v2.5m0 6V17m6-7v2.5m0 6v3");
}

</style>
