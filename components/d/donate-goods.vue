<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="z5mow-bmo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:donate-goods" /></template>
<style>
.z5mow-bmo {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M4.5 13h15v7.5h-15Zm-2.25-2.5L4.5 13m15 0l2.25-2.5M5 3.5h4.5V10H5Zm4.5 1.75h.5a1.75 1.75 0 0 1 0 3.5h-.5m5-5.25h4V10h-4Zm0 2.75h4");
}

</style>
