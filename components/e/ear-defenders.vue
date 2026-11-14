<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fnhutj1xr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:ear-defenders" /></template>
<style>
.fnhutj1xr {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M5.75 10.5v-1a6.25 6.25 0 0 1 12.5 0v1m-14.75 0H8a1 1 0 0 1 1 1v8a1 1 0 0 1-1 1H3.5a1 1 0 0 1-1-1v-8a1 1 0 0 1 1-1Zm12.5 0h4.5a1 1 0 0 1 1 1v8a1 1 0 0 1-1 1H16a1 1 0 0 1-1-1v-8a1 1 0 0 1 1-1Z");
}

</style>
