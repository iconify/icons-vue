<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="yva6amv5r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:bollard-light" /></template>
<style>
.yva6amv5r {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M8 11.5v-2a4 4 0 0 1 8 0v2Zm1.5 0v10m5-10v10m-8.5 0h12M7 4.5L5.5 3M17 4.5L18.5 3");
}

</style>
