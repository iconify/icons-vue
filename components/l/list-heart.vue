<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="m3n90-tvo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:list-heart" /></template>
<style>
.m3n90-tvo {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M4 5.5h.01M8 5.5h12.5M4 11.5h.01m3.99 0h12.5M4 17.5h.01m3.99 0h4m6 3.5s-3.25-2-3.25-4.25c0-1 .75-1.75 1.75-1.75c.5 0 1.25.5 1.5 1c.25-.5 1-1 1.5-1c1 0 1.75.75 1.75 1.75C21.25 19 18 21 18 21Z");
}

</style>
