<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="w20addcnl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:kitchen-cabinets" /></template>
<style>
.w20addcnl {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M5.625 3h2.25A2.625 2.625 0 0 1 10.5 5.625v3.75A2.625 2.625 0 0 1 7.875 12h-2.25A2.625 2.625 0 0 1 3 9.375v-3.75A2.625 2.625 0 0 1 5.625 3m10.5 0h2.25A2.625 2.625 0 0 1 21 5.625v3.75A2.625 2.625 0 0 1 18.375 12h-2.25A2.625 2.625 0 0 1 13.5 9.375v-3.75A2.625 2.625 0 0 1 16.125 3M2 16h20M3.5 16v5h17v-5M7.75 9.25h.01m8.49 0h.01");
}

</style>
