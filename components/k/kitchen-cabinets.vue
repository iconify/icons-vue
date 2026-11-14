<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zc3mw0bpu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:kitchen-cabinets" /></template>
<style>
.zc3mw0bpu {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M3 3h7.5v9H3Zm10.5 0H21v9h-7.5ZM2 16h20M3.5 16v5h17v-5M7.75 9.25h.01m8.49 0h.01");
}

</style>
