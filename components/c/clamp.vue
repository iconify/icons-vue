<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="pbp9l8bxk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:clamp" /></template>
<style>
.pbp9l8bxk {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M6.5 3h10.75q1.25 0 1.25 1.25V5q0 1.25-1.25 1.25h-7.5Q8.5 6.25 8.5 7.5v7q0 1.25 1.25 1.25h7.5q1.25 0 1.25 1.25v.75q0 1.25-1.25 1.25H6.5q-1.25 0-1.25-1.25V4.25Q5.25 3 6.5 3m8.75 18.25v-10m-2.25 0h4.5m-4.75 10h5");
}

</style>
