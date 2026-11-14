<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zdnn5zpkt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:food-safety-gloves" /></template>
<style>
.zdnn5zpkt {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M7 21v-9L5 9c-.5-1 .75-1.75 1.5-1L8 9.5V5c0-1 1.5-1 1.5 0V4c0-1 1.5-1 1.5 0v5l.5-4.5c.25-1 1.75-.75 1.5.25L12.5 9l2-1.5c1-.5 1.75.5 1 1.5L14 13v8Zm0-4h7");
}

</style>
