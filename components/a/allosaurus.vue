<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="j31vaac0d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:allosaurus" /></template>
<style>
.j31vaac0d {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.5 14.5C7 9.5 11 7 14 7l1-3.5h5.5q1 0 1 1v3h-4l-.5 2c-1 1-1.5 2-1.5 3.5l-.5 2.5c-1 1-4 1-6 0c-2-.5-4.5-.5-6.5-1Zm10 1.5v4.5m-3.5-5l-.5 5m7-9l2.75 1.75");
}

</style>
