<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wu71xgbzs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:barcode-food" /></template>
<style>
.wu71xgbzs {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M3 2.5v10m3.5-10v10m3.5-10v10m3.5-10v10m3.5-10v10m1.5 4.25c-1.75-1.25-3.5-.25-3.5 2c0 2 1.5 3.25 3.5 2.5c2 .75 3.5-.5 3.5-2.5c0-2.25-1.75-3.25-3.5-2Zm0-.25l1.25-2");
}

</style>
