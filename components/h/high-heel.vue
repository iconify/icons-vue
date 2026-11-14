<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="e82asmb0q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:high-heel" /></template>
<style>
.e82asmb0q {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M4 19h4c4 0 7-7.5 11-8h2V5h-1.5c-2.5 0-5 9-10.5 9H5.5q-3 0-3 3q0 2 1.5 2Zm16.5-8v9.5");
}

</style>
