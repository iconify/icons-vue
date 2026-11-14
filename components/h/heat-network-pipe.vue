<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="t5h7bgbbw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:heat-network-pipe" /></template>
<style>
.t5h7bgbbw {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.5 11.5h19v6h-19Zm3-2v10m13-10v10M10 2.5C8.5 4.25 11.5 6.25 10 8m4-5.5c-1.5 1.75 1.5 3.75 0 5.5");
}

</style>
