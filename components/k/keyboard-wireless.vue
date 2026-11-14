<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zxbqi03ak"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:keyboard-wireless" /></template>
<style>
.zxbqi03ak {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2 11h20v10H2Zm4 3.5h.01m3.99 0h.01m3.99 0h.01m3.99 0h.01M8.5 17.75h7M9.525 6.525a3.5 3.5 0 0 1 4.95 0M7.05 4.05a7 7 0 0 1 9.9 0");
}

</style>
