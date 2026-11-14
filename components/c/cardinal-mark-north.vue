<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ocdn1ub0b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:cardinal-mark-north" /></template>
<style>
.ocdn1ub0b {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m12 2.5l3.75 4.75h-7.5Zm0 4.75L15.75 12h-7.5ZM12 12v1.5m-4 4a4 4 0 1 0 8 0a4 4 0 1 0-8 0Z");
}

</style>
