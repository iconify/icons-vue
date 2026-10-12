<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ux2u0rbkq"><circle class="zz7891u5n"/><path class="g_a7evbzt"/><path class="fi1aodb8a"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:face-kiss-sharp" /></template>
<style>
.fi1aodb8a {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M10.25 14.25h1.5V16h-1.5h1.5v1.75h-1.5M19 6.8l-2.25-1.65V2.84h1.879l.381.68l.381-.68h1.879v2.31L19.02 6.8Z");
}

.g_a7evbzt {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M7.75 11.25h.01m5.49 0h.01");
}

.ux2u0rbkq {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
}

.zz7891u5n {
  cx: 10.75px;
  cy: 13.25px;
  r: 8px;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
