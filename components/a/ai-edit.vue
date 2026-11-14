<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jdvd5gbcs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:ai-edit" /></template>
<style>
.jdvd5gbcs {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m4 20l1-4.5L15.5 5A2.5 2.5 0 0 1 19 8.5L8.5 19Zm9.5-13l3.5 3.5m1 4.25q.5 2.75 3.25 3.25q-2.75.5-3.25 3.25q-.5-2.75-3.25-3.25q2.75-.5 3.25-3.25Z");
}

</style>
