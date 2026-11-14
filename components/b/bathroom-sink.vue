<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="m7kbxbb3l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:bathroom-sink" /></template>
<style>
.m7kbxbb3l {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M3 12h18c0 4.5-4 8-9 8s-9-3.5-9-8Zm7 0V5.5a2 2 0 0 1 2-2h2a2 2 0 0 1 2 2V7m0 2.5h.01");
}

</style>
