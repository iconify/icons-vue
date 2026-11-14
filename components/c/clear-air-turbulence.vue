<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ok1c5wbvm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:clear-air-turbulence" /></template>
<style>
.ok1c5wbvm {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m3 7.5l3-3l3 3l3-3l3 3l3-3l3 3m-16.5 6l3-3l3 3l3-3l3 3l3-3M3 19.5l3-3l3 3l3-3l3 3l3-3l3 3");
}

</style>
