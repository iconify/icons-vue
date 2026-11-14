<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xau3f3a4y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:blue-hour" /></template>
<style>
.xau3f3a4y {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M3.5 12a8.5 8.5 0 0 1 17 0m-18 0h19M18 15q0 3 3 3q-3 0-3 3q0-3-3-3q3 0 3-3Z");
}

</style>
