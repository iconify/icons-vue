<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="srd-kpbut"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:ai-response-format" /></template>
<style>
.srd-kpbut {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M7 3.5h-.5a2 2 0 0 0-2 2v4l-2 2.5l2 2.5v4a2 2 0 0 0 2 2H7m10-17h.5a2 2 0 0 1 2 2v4l2 2.5l-2 2.5v4a2 2 0 0 1-2 2H17M8.5 8h7m-7 4h7m-7 4H13");
}

</style>
