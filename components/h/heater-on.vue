<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="z8ziz8bvn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:heater-on" /></template>
<style>
.z8ziz8bvn {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M4.5 12.5a2.5 2.5 0 0 1 5 0a2.5 2.5 0 0 1 5 0a2.5 2.5 0 0 1 5 0v6a2.5 2.5 0 0 1-5 0a2.5 2.5 0 0 1-5 0a2.5 2.5 0 0 1-5 0Zm5 0v6m5-6v6M7 7.25Q5.75 6 7 4.75T7 2.5m5 4.75Q10.75 6 12 4.75t0-2.25m5 4.75Q15.75 6 17 4.75t0-2.25");
}

</style>
