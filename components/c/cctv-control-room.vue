<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qhdadwn6s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:cctv-control-room" /></template>
<style>
.qhdadwn6s {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M3 3h7v5H3Zm11 0h7v5h-7ZM3 10.75h7v5H3Zm11 0h7v5h-7ZM3.5 21.5V19h17v2.5");
}

</style>
