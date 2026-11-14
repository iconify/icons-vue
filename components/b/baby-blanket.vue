<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zt_x8bb9k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:baby-blanket" /></template>
<style>
.zt_x8bb9k {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M3 5q2.25-2 4.5 0T12 5t4.5 0T21 5v14a2 2 0 0 1-2 2H5a2 2 0 0 1-2-2Zm10 16l8-8");
}

</style>
