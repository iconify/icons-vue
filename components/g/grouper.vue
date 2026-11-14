<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fg2jrmbnv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:grouper" /></template>
<style>
.fg2jrmbnv {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.75 9C6 4.5 12.5 4.5 15.5 10l4-3.5c2 2.5 2 8.5 0 11l-4-3.5c-3 5.5-9.5 5.5-12.75 1l3.5-3Zm5.75.5h.01");
}

</style>
