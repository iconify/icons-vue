<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="m54g71b4b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:category-plumbing" /></template>
<style>
.m54g71b4b {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M5 7.5h3a2.5 2.5 0 0 1 2.5 2.5A2.5 2.5 0 0 1 8 12.5H5A2.5 2.5 0 0 1 2.5 10A2.5 2.5 0 0 1 5 7.5m5.5 2.5h5a3.5 3.5 0 0 1 3.5 3.5V15m-2 0h4M6.5 3.5v4m-3-4h6M19 17.75c-1 1.25-1.75 2-1.75 2.25a1.75 1.75 0 0 0 3.5 0c0-.25-.75-1-1.75-2.25");
}

</style>
