<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wq2ql9bpz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:camera-floodlight" /></template>
<style>
.wq2ql9bpz {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M3.5 3.5h17V9h-17Zm4.5 13a4 4 0 1 0 8 0a4 4 0 1 0-8 0ZM6.5 12L5 15.5M17.5 12l1.5 3.5m-7 1h.01");
}

</style>
