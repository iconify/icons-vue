<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ux2u0rbkq"><circle class="c6vt1lbds"/><path class="ffoicec9o"/><path class="af85zkb7t"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:face-upside-down-sharp" /></template>
<style>
.af85zkb7t {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M9 14h.01M15 14h.01");
}

.c6vt1lbds {
  cx: 12px;
  cy: 12px;
  r: 9.25px;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.ffoicec9o {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m8.5 9.75l1.385-2h4.23l1.385 2");
}

.ux2u0rbkq {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
}

</style>
