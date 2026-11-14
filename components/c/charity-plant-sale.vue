<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rrymi0dpd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:charity-plant-sale" /></template>
<style>
.rrymi0dpd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M3 12h9l-1 8.5H4Zm4.5 0V7.5m0 1.5c0-2.5-2-4-4.75-4c0 2.5 2 4 4.75 4Zm0-1.5C7.5 5 9.5 3 12.25 3c0 2.5-2 4.5-4.75 4.5Zm7 8.25a.75.75 0 0 1 .75-.75h3.25l3 3.25l-3 3.25h-3.25a.75.75 0 0 1-.75-.75Z");
}

</style>
