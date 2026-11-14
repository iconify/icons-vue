<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="o316e-b1h"/><path class="ys-5hwbls"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:livestock-tracker" /></template>
<style>
.o316e-b1h {
  d: path("m6.75 16.75l-.75-5a.75.75 0 0 1 .75-.75h4.75a.75.75 0 0 1 .75.75l-.75 5m-6.25 0H13V21H5.25Z");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.ys-5hwbls {
  d: path("M6.25 12.75c-1.65.22-3.05-.12-3.75-1.25c1.05-.62 2.45-.62 3.5 0m6.25 1.25c1.45.22 2.85-.12 3.5-1.25c-1-.62-2.4-.62-3.5 0M7.5 11c-.1-1-.45-1.7-1.5-2m5 2c-.1-1 .25-1.7 1.25-2m5.75.75c.05.1-2.95-2.5-3-4.75a3 3 0 0 1 6 0c.05 2.25-2.95 4.85-3 4.75ZM18 5h.01");
}

</style>
