<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qab0gep6e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:air-pinch" /></template>
<style>
.qab0gep6e {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M9.5 13v3a5.5 5.5 0 0 0 11 0V7m-18 6a3.5 3.5 0 1 0 7 0a3.5 3.5 0 1 0-7 0Zm10.75 0V3.5m3.5 9.5V4.25");
}

</style>
