<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="c7b25ac7j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:lavender-field" /></template>
<style>
.c7b25ac7j {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.5 20.5h19M5 20.5L3 13m2 7.5V12m0 8.5L7 13m5 7.5L10 13m2 7.5V12m0 8.5l2-7.5m5 7.5L17 13m2 7.5V12m0 8.5l2-7.5M2.5 8q2-2.5 4 0q2-2.5 4 0q2-2.5 4 0q2-2.5 4 0q2-2.5 3-.5");
}

</style>
