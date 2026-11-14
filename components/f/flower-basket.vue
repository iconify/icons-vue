<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="w-wejpb8x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:flower-basket" /></template>
<style>
.w-wejpb8x {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M3 14h18l-2 7.5H5Zm1 0c0-6 16-6 16 0M4 17.75h16M6.5 2.5l2 1.5l2-1.5V5a2 2 0 0 1-4 0Zm2 4.5v7m5-11.5l2 1.5l2-1.5V5a2 2 0 0 1-4 0Zm2 4.5v7");
}

</style>
