<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="cs8_mhbmk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:eraser" /></template>
<style>
.cs8_mhbmk {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m7.5 20.5l-4-4c-.75-.75-.75-2.25 0-3l9-9c.75-.75 2.25-.75 3 0L20 9c.75.75.75 2.25 0 3l-8.5 8.5Zm4 0H21M7.5 9.5L15 17");
}

</style>
