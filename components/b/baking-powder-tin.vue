<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="eoo37sbzs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:baking-powder-tin" /></template>
<style>
.eoo37sbzs {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M3 7h9.5v14.5H3Zm-.5-3.5H13V7H2.5Zm.5 8h9.5M3 17h9.5m3 0h6a3 3 0 0 1-6 0Zm2.5 0l-5.5-2.75");
}

</style>
