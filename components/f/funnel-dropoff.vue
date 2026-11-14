<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="cbfi8132l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:funnel-dropoff" /></template>
<style>
.cbfi8132l {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.5 3.5h17L13.25 11v8.5l-4.5-2V11Zm13 4.75h.01m2.49 5s-2.25 3-2.25 4.75a2.25 2.25 0 0 0 4.5 0c0-1.75-2.25-4.75-2.25-4.75Z");
}

</style>
