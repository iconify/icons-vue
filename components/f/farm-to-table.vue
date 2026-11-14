<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="w-kbtwbpe"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:farm-to-table" /></template>
<style>
.w-kbtwbpe {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M7.5 10.5a4.5 4.5 0 1 0 9 0a4.5 4.5 0 1 0-9 0ZM3 3v2.75a1.25 1.25 0 0 0 2.5 0V3M4.25 7v12M21 12.2V3q-2 1.5-2 5v2h2m-6 11.5c0-4.5 2-6.5 6.5-6.5c0 4.5-2 6.5-6.5 6.5Zm0 0l3.5-3.5");
}

</style>
