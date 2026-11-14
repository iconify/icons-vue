<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="f4-_xwbzn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:fan-handheld" /></template>
<style>
.f4-_xwbzn {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m12 15l-8.5-3a4 4 0 0 1 3.25-4.25A4 4 0 0 1 12 6a4 4 0 0 1 5.25 1.75A4 4 0 0 1 20.5 12Zm0 0v5.5m0-5.5L6.75 7.75M12 15V6m0 9l5.25-7.25");
}

</style>
