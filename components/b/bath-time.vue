<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="se0uzfbys"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:bath-time" /></template>
<style>
.se0uzfbys {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M3 11h18v2a5 5 0 0 1-5 5H8a5 5 0 0 1-5-5Zm4 7l-1 2.5M17 18l1 2.5M6.5 6a2 2 0 1 0 4 0a2 2 0 1 0-4 0ZM13 4a1.5 1.5 0 1 0 3 0a1.5 1.5 0 1 0-3 0Z");
}

</style>
