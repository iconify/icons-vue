<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="nhztcgsck"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:facial-steamer" /></template>
<style>
.nhztcgsck {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M3.25 13.5h17.5a8.75 7.75 0 0 1-17.5 0m6.25-3Q8 8.625 9.5 6.75c1.5-1.875 1-2.5 0-3.75m5 7.5q-1.5-1.875 0-3.75c1.5-1.875 1-2.5 0-3.75");
}

</style>
