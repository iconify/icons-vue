<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="w2zrn6u6g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:chromatid" /></template>
<style>
.w2zrn6u6g {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M7 3q5 4 5 9t-5 9q-2 .5-3-1.5Q8.5 16 8.5 12T4 4.5q1-2 3-1.5Zm10 0q-5 4-5 9t5 9q2 .5 3-1.5q-4.5-3.5-4.5-7.5T20 4.5q-1-2-3-1.5Z");
}

</style>
