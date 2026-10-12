<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ux2u0rbkq"><circle class="c6vt1lbds"/><path class="rd4ffbunp"/><path class="sn9givwtn"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:face-sleep-mask-sharp" /></template>
<style>
.c6vt1lbds {
  cx: 12px;
  cy: 12px;
  r: 9.25px;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.rd4ffbunp {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M9 8.75h.01m5.99 0h.01");
}

.sn9givwtn {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M9.75 12h6.75v6h-9v-6zM7.5 13.25L3.3 11.5m13.2 1.75l4.2-1.75M9.75 15h4.5");
}

.ux2u0rbkq {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
}

</style>
