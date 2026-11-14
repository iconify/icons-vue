<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="tb9coabsb"/><path class="y973-nb8k"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:factory-floor-plan" /></template>
<style>
.tb9coabsb {
  d: path("M10 20.5H4A1.5 1.5 0 0 1 2.5 19V5A1.5 1.5 0 0 1 4 3.5h16A1.5 1.5 0 0 1 21.5 5v14a1.5 1.5 0 0 1-1.5 1.5h-6");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.y973-nb8k {
  d: path("M5.25 6.25h3v4.25h-3Zm5.25 0h3v4.25h-3Zm5.25 0h3v4.25h-3Z");
}

</style>
