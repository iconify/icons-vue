<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qtg00k30j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:compression-sack" /></template>
<style>
.qtg00k30j {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M10 6c-4 1-5 3-5 6v5.5c0 2 2 3 7 3s7-1 7-3V12c0-3-1-5-5-6Zm.5 0q0-3.5 1.5-3.5T13.5 6M5 14.5L19 12M5 17.5L19 15");
}

</style>
