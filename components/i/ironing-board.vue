<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="h1sqdkbql"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:ironing-board" /></template>
<style>
.h1sqdkbql {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M8.25 6.25C8.75 4.5 10 3.5 11.75 3.5H15a1 1 0 0 1 1 1v1.75ZM3.75 8.5H16c2.75 0 5.25.75 5.25 1.75S18.75 12 16 12H3.75a1 1 0 0 1-1-1V9.5a1 1 0 0 1 1-1m3 3.5L16 21.25M15.75 12L6.5 21.25");
}

</style>
