<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wxzj7wbaw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:fishing-knife" /></template>
<style>
.wxzj7wbaw {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M7.25 14.25L20.5 3.5q-2 8-10.75 13.25ZM3.525 18L6 15.525a1.75 1.75 0 0 1 2.475 0a1.75 1.75 0 0 1 0 2.475L6 20.475a1.75 1.75 0 0 1-2.475 0a1.75 1.75 0 0 1 0-2.475");
}

</style>
