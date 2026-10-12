<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ux2u0rbkq"><circle class="c6vt1lbds"/><path class="nckm-wble"/><path class="ucai-vb8d"/><path class="aa5t66bzh"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:face-confused-sharp" /></template>
<style>
.aa5t66bzh {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M9 16.5c1-1 2-.25 3-.75l2-1l1 .75");
}

.c6vt1lbds {
  cx: 12px;
  cy: 12px;
  r: 9.25px;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.nckm-wble {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m7.5 7.75l1.25-.833L10 7.75m4 0L16.5 7");
}

.ucai-vb8d {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M9 10.25h.01M15 10h.01");
}

.ux2u0rbkq {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
}

</style>
