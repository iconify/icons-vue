<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="i325c2bri"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:category-travel-luggage" /></template>
<style>
.i325c2bri {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M5 7h14v14H5Zm4 0V4.5a1 1 0 0 1 1-1h4a1 1 0 0 1 1 1V7m-5.5 4v6m5-6v6");
}

</style>
