<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="w41fy3bgc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:highway" /></template>
<style>
.w41fy3bgc {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M9.5 2.75h5q1 0 1.3.95l5.15 16.6q.3.95-.7.95H3.75q-1 0-.7-.95L8.2 3.7q.3-.95 1.3-.95m1 2.75l-.25 2m-.25 3L9.75 13m-.25 3l-.25 3M13.5 5.5l.25 2m.25 3l.25 2.5m.25 3l.25 3");
}

</style>
