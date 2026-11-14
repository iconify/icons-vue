<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="dgy0ec8jg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:geologist" /></template>
<style>
.dgy0ec8jg {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M3.5 9h15m-13 0a5.5 5.5 0 0 1 11 0M7 9v1.5a4 4 0 0 0 8 0V9M4 21.5c0-2.5 3-4.25 7-4.25s7 1.75 7 4.25m2.75 0V13m-2.25 0H22");
}

</style>
