<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vsyes-bjt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:chart-anchorage-symbol" /></template>
<style>
.vsyes-bjt {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.5 6.5V5A2.5 2.5 0 0 1 5 2.5h1.5m3.5 0h4m3.5 0H19A2.5 2.5 0 0 1 21.5 5v1.5m0 3.5v4m0 3.5V19a2.5 2.5 0 0 1-2.5 2.5h-1.5m-3.5 0h-4m-3.5 0H5A2.5 2.5 0 0 1 2.5 19v-1.5m0-3.5v-4m7.75-3a1.75 1.75 0 1 0 3.5 0a1.75 1.75 0 1 0-3.5 0M12 8.75v9.75m-2.5-8h5m-6.5 4a4 4 0 0 0 8 0");
}

</style>
