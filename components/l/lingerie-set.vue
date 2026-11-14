<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="w7gzgyotj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:lingerie-set" /></template>
<style>
.w7gzgyotj {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.5 15.25q0-5 4-1.5q4-3.5 4 1.5Zm10.75-5.5h8.25v2c-2 1-2.75 3-2.75 5H16c0-2-.75-4-2.75-5Zm-10 2.5l1.25-5m5.25 5l-1.25-5");
}

</style>
