<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="x-950obik"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:iceberg-penguins" /></template>
<style>
.x-950obik {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M3 15.5L7 10h6.5l2 2.25l2-1.25l3.5 4.5ZM9 10c-.75-2.5-.25-5 1.5-6.5c.75-.75 1.75-.25 2 .5l1.25.75l-1 .5C13.5 7 13.5 8.5 13 10M2.5 19.5q2.25-1.25 4.75 0q2.25 1.25 4.75 0q2.25-1.25 4.75 0q2.25 1.25 4.75 0");
}

</style>
