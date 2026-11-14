<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="m4cl-bbmt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:layers-front" /></template>
<style>
.m4cl-bbmt {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M9.5 3.5L16 7.25L9.5 11L3 7.25ZM3 11.25L9.5 15l6.5-3.75M3 15l6.5 3.75L16 15m3.5 5V4.25m-2 2l2-2l2 2");
}

</style>
