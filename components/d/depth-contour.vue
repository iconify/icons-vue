<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="uaz5_tb4l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:depth-contour" /></template>
<style>
.uaz5_tb4l {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M3 4.5c4-2 6 2 9 0s5 2 9 0m-16 4c3-2 5 2 7 0s4 2 7 0m-12 4c2-2 4 2 5 0s3 2 5 0m-14 8l18-5");
}

</style>
