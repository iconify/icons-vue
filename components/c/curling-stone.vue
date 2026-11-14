<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="yjcdrhbjs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:curling-stone" /></template>
<style>
.yjcdrhbjs {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M5.5 10h13a2 2 0 0 1 2 2v4a2 2 0 0 1-2 2h-13a2 2 0 0 1-2-2v-4a2 2 0 0 1 2-2Zm3 0V7.5A1.5 1.5 0 0 1 10 6h8M3.5 14h17");
}

</style>
