<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="cekbdq25b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:crayons" /></template>
<style>
.cekbdq25b {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M5 8.5h3V20H5ZM10.5 5h3v15h-3ZM16 8.5h3V20h-3Zm-11 0l1.5-3l1.5 3M10.5 5L12 2.5L13.5 5M16 8.5l1.5-3l1.5 3");
}

</style>
