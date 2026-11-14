<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qvjie0blx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:apron-feeder" /></template>
<style>
.qvjie0blx {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m3 2.5l3.5 6h4l3.5-6m-8.043 8.906l13.625 4.959a2.25 2.25 0 0 1 1.345 2.884a2.25 2.25 0 0 1-2.884 1.345L4.418 15.635a2.25 2.25 0 0 1-1.345-2.884a2.25 2.25 0 0 1 2.884-1.345m2.584.941l-1.539 4.228m5.768-2.689l-1.54 4.228m5.768-2.689l-1.539 4.228");
}

</style>
