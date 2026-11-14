<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="eouqsac5h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:emergency-candle" /></template>
<style>
.eouqsac5h {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M8.5 12h7v9.5h-7Zm3.5 0V9.25m0-7c1.75 2 2.5 3.25 2.5 4.5a2.5 2.5 0 0 1-5 0c0-1.25.75-2.5 2.5-4.5Z");
}

</style>
