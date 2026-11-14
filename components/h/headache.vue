<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vmnjhwbgr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:headache" /></template>
<style>
.vmnjhwbgr {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M7.25 21.5V18c-2.25-1.5-3-3.5-3-5.75c0-3.75 2.75-6.5 6.5-6.5C14 5.75 16.5 8 16.5 11.5l1.5 3q0 .75-.75.75h-.75v2c0 1-.75 1.75-1.5 1.75h-1.75v2.5m2.25-19L17 4l-1.25 1.25l1.5 1.5M18.5 4.5L20 6l-1.25 1.25l1.5 1.5m-5.75 2h.01");
}

</style>
