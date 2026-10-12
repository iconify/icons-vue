<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ux2u0rbkq"><path class="g0bmy-b-h"/><circle class="ksuof3r5e"/><path class="y0ijwrb2n"/><circle class="o1khsik-g"/><path class="px0dp75uh"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:garbage-truck-sharp" /></template>
<style>
.g0bmy-b-h {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M8.25 5.25H14V9h4l.68.73l1.89 2.04l.68.73v4.25H5.75V12.5h-3V9.75l.71-.71l3.08-3.08l.71-.71zM14 9v7.75");
}

.ksuof3r5e {
  cx: 8.75px;
  cy: 19px;
  r: 2.25px;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.o1khsik-g {
  cx: 17.75px;
  cy: 19px;
  r: 2.25px;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.px0dp75uh {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M17.75 19h.01");
}

.ux2u0rbkq {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
}

.y0ijwrb2n {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M8.75 19h.01");
}

</style>
