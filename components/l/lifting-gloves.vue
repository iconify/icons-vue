<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hz20x4bkt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:lifting-gloves" /></template>
<style>
.hz20x4bkt {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M6.5 9.5h11V18a2.5 2.5 0 0 1-2.5 2.5H9A2.5 2.5 0 0 1 6.5 18Zm0 4.5L4 11.5m5-2V6m3 3.5V5m3 4.5V6M6.5 16.5h11");
}

</style>
