<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="x8g7ckjch"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:curler-delivery" /></template>
<style>
.x8g7ckjch {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M9.5 8.5H20a1.5 1.5 0 0 1 1.5 1.5v5a1.5 1.5 0 0 1-1.5 1.5H9.5A1.5 1.5 0 0 1 8 15v-5a1.5 1.5 0 0 1 1.5-1.5Zm2.5 0V6a2 2 0 0 1 2-2h5.5m-17 15.5h19M8 12.5h13.5m-19 0h2.75");
}

</style>
