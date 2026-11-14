<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="d9hsbh4us"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:jacket-platform" /></template>
<style>
.d9hsbh4us {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M3.5 3.5h17v3h-17Zm3.5 3l-2 10m12-10l2 10M7 6.5l12 10m-2-10l-12 10M2.5 20q2.5-1.5 5 0t5 0t5 0t4 0");
}

</style>
