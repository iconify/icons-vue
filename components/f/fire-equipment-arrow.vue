<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="sq_ubpb0z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:fire-equipment-arrow" /></template>
<style>
.sq_ubpb0z {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M7.5 7za3.5 3.5 0 0 1 3.5 3.5v7A3.5 3.5 0 0 1 7.5 21A3.5 3.5 0 0 1 4 17.5v-7A3.5 3.5 0 0 1 7.5 7M6 7V4h3v3m0-3h4l3 4.5m-1 10h6.5m-3-3l3 3l-3 3");
}

</style>
