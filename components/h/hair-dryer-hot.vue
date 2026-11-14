<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="v7m9r8slj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:hair-dryer-hot" /></template>
<style>
.v7m9r8slj {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M7 4h7l2 1.5v5L14 12H7a4 4 0 0 1 0-8Zm-.5 8H10v8.5H6.5Zm12-5.5q.75-1 1.5 0t1.5 0m-3 3q.75-1 1.5 0t1.5 0");
}

</style>
