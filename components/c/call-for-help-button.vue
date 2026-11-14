<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="w7k-7qb1h"/><path class="b25cpibog"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:call-for-help-button" /></template>
<style>
.b25cpibog {
  d: path("M5.75 12a3.75 3.75 0 1 0 7.5 0a3.75 3.75 0 1 0-7.5 0Zm3.75-1.75v2m0 1.75h.01m5.735-6.821a7.5 7.5 0 0 1 0 9.642M18.593 6.75a10.5 10.5 0 0 1 0 10.5");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.w7k-7qb1h {
  d: path("M4.5 2.5h10v19h-10Zm5 2.5h.01M9.5 19h.01");
}

</style>
