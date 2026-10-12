<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ctd57hz5q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:impact-driver-sharp" /></template>
<style>
.ctd57hz5q {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M8.5 5h4v5.5H11l.5 5.25H7.25l.5-5.25h.75a2.75 2.75 0 0 1 0-5.5Zm4 .75h4v4h-4zm4 2h2.25M5 15.75h9v4.5H5z");
}

</style>
