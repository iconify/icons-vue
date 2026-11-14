<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xz78v1bpa"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:industrial-sewing-machine" /></template>
<style>
.xz78v1bpa {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M5 16V6a2 2 0 0 1 2-2h12a2 2 0 0 1 2 2v3H9v7m-6.5 0h19v4.5h-19Zm15-7v4");
}

</style>
