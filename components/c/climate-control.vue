<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="saieno8wx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:climate-control" /></template>
<style>
.saieno8wx {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M13.016 19H2.5V9.5l8-6.5l8 6.5v1.484M7.75 10v9m5.5-9v8m3.5-.25V15a1.25 1.25 0 0 1 2.5 0v2.75a2.25 2.25 0 1 1-2.5 0Z");
}

</style>
