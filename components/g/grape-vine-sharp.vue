<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><path class="q6rjwgkiy"/><circle class="m3m9nrmce"/><circle class="hlk9z-gue"/><circle class="cxzxrma2a"/><circle class="k0kd3bb_a"/><circle class="sjcg-y_6j"/><circle class="zoxheb0fq"/><path class="xe_1eb_xl"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:grape-vine-sharp" /></template>
<style>
.cxzxrma2a {
  cx: 13.5px;
  cy: 10px;
  r: 1.5px;
}

.hlk9z-gue {
  cx: 9px;
  cy: 10px;
  r: 1.5px;
}

.k0kd3bb_a {
  cx: 6.75px;
  cy: 13.9px;
  r: 1.5px;
}

.m3m9nrmce {
  cx: 4.5px;
  cy: 10px;
  r: 1.5px;
}

.q6rjwgkiy {
  d: path("M2.75 5.25q3.75-2.25 7.5 0c2.5 1.5 5.5 1.5 8 0l2.045-1.227l.955-1.273M9 5.25V8.5");
}

.sjcg-y_6j {
  cx: 11.25px;
  cy: 13.9px;
  r: 1.5px;
}

.x2cwu0gfd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.xe_1eb_xl {
  d: path("M16 6q-2.72 7.1 4.5 9.5Q23.22 8.4 16 6Z");
}

.zoxheb0fq {
  cx: 9px;
  cy: 17.8px;
  r: 1.5px;
}

</style>
