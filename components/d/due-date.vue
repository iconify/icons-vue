<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><rect class="tydl24byx"/><path class="h7-vqrppe"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:due-date" /></template>
<style>
.h7-vqrppe {
  d: path("M3.75 10h16.5M8 2.75v4m8-4v4m-7 11.5V13h6l-1.5 1.75L15 16.5H9");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.tydl24byx {
  width: 16.5px;
  height: 16.5px;
  x: 3.75px;
  y: 4.75px;
  rx: 2.5px;
}

</style>
