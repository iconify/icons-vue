<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ux2u0rbkq"><path class="fcg6c-uxk"/><path class="d2vtgj4-r"/><path class="t2mdzfbts"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:calendar-year-sharp" /></template>
<style>
.d2vtgj4-r {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M6.5 4h14.25v13.75");
}

.fcg6c-uxk {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M3.25 7h14.5v14.25H3.25zm0 4.5h14.5");
}

.t2mdzfbts {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M7 15h.01m3.49 0h.01M14 15h.01M7 18h.01m3.49 0h.01");
}

.ux2u0rbkq {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
}

</style>
