<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="dwqkzvbdq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:air-sensor" /></template>
<style>
.dwqkzvbdq {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.5 6h11v12h-11Zm3 4.5h5m-5 3h5m5.75-4c1.5-1.5 3.25 1.5 5.25 0m-5.25 5c1.5-1.5 3.25 1.5 5.25 0");
}

</style>
