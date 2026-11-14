<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="scihoybct"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:coffee-ready" /></template>
<style>
.scihoybct {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M4 11h12.5v5.5A4.5 4.5 0 0 1 12 21H8.5A4.5 4.5 0 0 1 4 16.5Zm12.5 1.5h1a2.5 2.5 0 0 1 0 5h-1M8 3C6.75 4.5 9.25 6 8 7.5M12.5 3c-1.25 1.5 1.25 3 0 4.5");
}

</style>
