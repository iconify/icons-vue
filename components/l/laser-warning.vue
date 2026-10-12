<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="l1mthztqi"/><circle class="ougho4bnr"/><path class="ulqmmi3nt"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:laser-warning" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.l1mthztqi {
  d: path("m12.98 4.99l7.29 13.02q.98 1.74-1.02 1.74H4.75q-2 0-1.02-1.74l7.29-13.02q.98-1.74 1.96 0");
}

.ougho4bnr {
  cx: 10.5px;
  cy: 14.5px;
  r: 1.25px;
}

.ulqmmi3nt {
  d: path("M11.75 14.5H16m-5.5-3v.5m0 5v.5m-3-3H8m.4-2.1l.35.35M8.4 16.6l.35-.35");
}

</style>
