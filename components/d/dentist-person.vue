<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="m8r76hb0s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:dentist-person" /></template>
<style>
.m8r76hb0s {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M13.572 20.5H4c-.6 0-1-.4-1-1c0-3.25 3.25-5.5 7.5-5.5c.611 0 1.202.047 1.765.136M6.5 7a4 4 0 1 0 8 0a4 4 0 1 0-8 0Zm8.5 8c0-1.25 1-1.75 2-1.75c.5 0 .75.25 1 .5c.25-.25.5-.5 1-.5c1 0 2 .5 2 1.75c0 1.5-.75 2.5-1 4l-.5 1.5q-.25.5-.75 0L18 19l-.75 1.5q-.5.5-.75 0L16 19c-.25-1.5-1-2.5-1-4Z");
}

</style>
