<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bo0cip5zc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:ecologist" /></template>
<style>
.bo0cip5zc {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M3.5 7.5h14M7 7.5V5a1.5 1.5 0 0 1 1.5-1.5h4A1.5 1.5 0 0 1 14 5v2.5m-7 0V9a3.5 3.5 0 0 0 7 0V7.5m-11 13c0-3.5 3.25-5.25 7.5-5.25c1.333 0 2.567.172 3.634.516M15.5 21.5q0-6 6-6q0 6-6 6Z");
}

</style>
