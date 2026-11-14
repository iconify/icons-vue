<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="yrr0stbvk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:grease-tub" /></template>
<style>
.yrr0stbvk {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M3.5 11h17L19 19a1.5 1.5 0 0 1-1.5 1.5h-11A1.5 1.5 0 0 1 5 19Zm3 0C6 8.5 8 7 10 7.5c0-2.5 2-4 4.5-3c-1 1-.5 2.5.5 3c2 0 3 1.5 2.5 3.5");
}

</style>
