<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qg5fv5b2r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:heat-up" /></template>
<style>
.qg5fv5b2r {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.5 16.5h12V21h-12Zm3.5-3q-1.5-2.5 0-5t0-5m5 10q-1.5-2.5 0-5t0-5M18.5 21V3.5m-3 3l3-3l3 3");
}

</style>
