<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="y_w083hdv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:keyboard-x" /></template>
<style>
.y_w083hdv {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2 6h20v12H2Zm4 3.25h.01m3.99 0h.01m3.99 0h.01m3.99 0h.01m-7.76 3.25l3.5 3.5m0-3.5l-3.5 3.5");
}

</style>
