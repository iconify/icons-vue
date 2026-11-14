<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ztsp99b3h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:live-broadcast-check" /></template>
<style>
.ztsp99b3h {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M6 3.5h6.5A3.5 3.5 0 0 1 16 7v5a3.5 3.5 0 0 1-3.5 3.5H6A3.5 3.5 0 0 1 2.5 12V7A3.5 3.5 0 0 1 6 3.5m10 4l5.5-3v8.535m-2.05.347L16 11.5m-4.5-4h.01M14.75 18l2 2L21 15.75");
}

</style>
