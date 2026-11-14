<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="u-h7vn2fb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:boarding-ladder" /></template>
<style>
.u-h7vn2fb {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.5 6h19m-17 2.5V5.25a1.75 1.75 0 0 1 3.5 0V21.5m11.5-13V5.25a1.75 1.75 0 0 0-3.5 0V21.5m-8-11h8m-8 4h8m-8 4h8");
}

</style>
