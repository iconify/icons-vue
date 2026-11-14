<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="sq8qf98jq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:days-of-week" /></template>
<style>
.sq8qf98jq {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.5 4h19v16.5h-19Zm0 5h19m-14-6.5V6m9-3.5V6M5 13.5v2m2.5-1h.01m2.24 0h.01m2.24 0h.01m2.24 0h.01m2.24 0h.01m2.24 0h.01");
}

</style>
