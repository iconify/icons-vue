<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="j5684cu_x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:baby-plate" /></template>
<style>
.j5684cu_x {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.25 12a7.5 7.5 0 1 0 15 0a7.5 7.5 0 1 0-15 0Zm0 0h15m-7.5 0v7.5M19 7a1.5 2.5 0 1 0 3 0a1.5 2.5 0 1 0-3 0Zm1.5 2.5V20");
}

</style>
