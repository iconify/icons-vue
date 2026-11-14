<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="d8xx1rpid"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:foul-warning" /></template>
<style>
.d8xx1rpid {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m16.229 12.253l-3.01 8.27l-9.397-3.42L8.781 3.477l9.397 3.42l-1.402 3.853M19 13.5v5m0 3h.01");
}

</style>
