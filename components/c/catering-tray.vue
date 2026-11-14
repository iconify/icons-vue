<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="g_sdex_7j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:catering-tray" /></template>
<style>
.g_sdex_7j {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.5 12h19L19 19.5H5ZM4 12l1-4.5l2.5 1.25L9.75 6l2.5 2l2.25-2.75l2.5 2.5l2.25-1L20 12M7 15.75h10");
}

</style>
