<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="x4uwelbns"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:bagged-salad" /></template>
<style>
.x4uwelbns {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M5.5 21.5C4.5 17 4.75 13 6 9l1.5 1.5L9 9l1.5 1.5L12 9l1.5 1.5L15 9l1.5 1.5L18 9c1.25 4 1.5 8 .5 12.5ZM12 9c-2.5-4 .5-6.5 6.5-6.5C18.5 7 16 9 15 9");
}

</style>
