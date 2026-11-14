<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="kjnkq3ezq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:chart-reference-line" /></template>
<style>
.kjnkq3ezq {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.5 21.5h19M5 12.5h1A1.5 1.5 0 0 1 7.5 14v6A1.5 1.5 0 0 1 6 21.5H5A1.5 1.5 0 0 1 3.5 20v-6A1.5 1.5 0 0 1 5 12.5M11.5 4h1A1.5 1.5 0 0 1 14 5.5V20a1.5 1.5 0 0 1-1.5 1.5h-1A1.5 1.5 0 0 1 10 20V5.5A1.5 1.5 0 0 1 11.5 4M18 7h1a1.5 1.5 0 0 1 1.5 1.5V20a1.5 1.5 0 0 1-1.5 1.5h-1a1.5 1.5 0 0 1-1.5-1.5V8.5A1.5 1.5 0 0 1 18 7M2.5 9.5h5.25m4 0h.5m3.5 0H14.5m3.75 0h.5");
}

</style>
