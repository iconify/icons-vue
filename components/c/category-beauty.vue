<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xqg5v9b9x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:category-beauty" /></template>
<style>
.xqg5v9b9x {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M8.75 16h6.5A1.75 1.75 0 0 1 17 17.75v2a1.75 1.75 0 0 1-1.75 1.75h-6.5A1.75 1.75 0 0 1 7 19.75v-2A1.75 1.75 0 0 1 8.75 16M10 11.5h4a1.5 1.5 0 0 1 1.5 1.5v1.5A1.5 1.5 0 0 1 14 16h-4a1.5 1.5 0 0 1-1.5-1.5V13a1.5 1.5 0 0 1 1.5-1.5m-.25 0v-5l4.5-3v8");
}

</style>
