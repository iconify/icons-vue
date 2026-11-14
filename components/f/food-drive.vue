<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="e5uw6wbob"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:food-drive" /></template>
<style>
.e5uw6wbob {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.5 12h19v9h-19ZM4 12V7.5a1.75 1.25 0 0 1 3.5 0V12M4 7.5a1.75 1.25 0 0 0 3.5 0m2.75 4.5V5a1.75 1.25 0 0 1 3.5 0v7m-3.5-7a1.75 1.25 0 0 0 3.5 0m2.75 7V7.5a1.75 1.25 0 0 1 3.5 0V12m-3.5-4.5a1.75 1.25 0 0 0 3.5 0");
}

</style>
