<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mhuvn38kq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:gas-hob" /></template>
<style>
.mhuvn38kq {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.5 16h19v4.5h-19Zm2-2.75h6m3 0h6M7.5 2.5c.75 2 3 3 3 5.25a3 3 0 0 1-6 0c0-1.25.5-2 1.25-2.75C6 6 6.5 6.5 7 6.5c0-1.5-.25-2.75.5-4Z");
}

</style>
