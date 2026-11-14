<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="c1jc3ps0e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:fracture-material" /></template>
<style>
.c1jc3ps0e {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M10 3.5H5a2 2 0 0 0-2 2v13a2 2 0 0 0 2 2h4.5l1.5-4L9 12l2.5-4Zm3.5 0H19a2 2 0 0 1 2 2v13a2 2 0 0 1-2 2h-6l1.5-4l-2-4.5L15 8Z");
}

</style>
