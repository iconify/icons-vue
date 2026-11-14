<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="r3uk1966d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:floodlight" /></template>
<style>
.r3uk1966d {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m3.5 6.5l8-2.5v10l-8-2.5Zm4 6.25v7.75m-3 0h6m4-15.5l5-2m-5 6h6m-6 4l5 2");
}

</style>
