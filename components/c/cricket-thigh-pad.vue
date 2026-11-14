<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ydhxf-bzx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:cricket-thigh-pad" /></template>
<style>
.ydhxf-bzx {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M8 2.5C13 2.5 18 4 18 9v8c0 2.5-2 4.5-4.5 4.5H10c-2.5 0-4-2-4-4.5V4.5c0-1.1.9-2 2-2ZM10.5 6v12M14 7v11M2.5 8H6m-3.5 7H6");
}

</style>
