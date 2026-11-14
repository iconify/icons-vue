<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zcew5ebpm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:garment-steamer" /></template>
<style>
.zcew5ebpm {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M3.5 10H15v3.5H3.5Zm9 3.5H15l3.75 6.25l-2.25 1.5Zm-6-1.75h.01m2.74 0h.01m2.74 0h.01M18.75 20c1.75-.5 2.75-2.5 2.5-5M6 8.5c-1-1.5 1-3 0-5m3.25 5c-1-1.5 1-3 0-5m3.25 5c-1-1.5 1-3 0-5");
}

</style>
