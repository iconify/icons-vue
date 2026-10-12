<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><path class="lc25cmbcu"/><circle class="u-10n5mpy"/><circle class="oof2upb3i"/><circle class="szw-6_b5h"/><path class="n_jx8ebpc"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:farmers-market-sharp" /></template>
<style>
.lc25cmbcu {
  d: path("M5.3 2.75h14.2l.23.77l1.29 4.21l.23.77H2.75l.23-.77l1.29-4.21l.23-.77zm3.95.5L8.75 8m6-4.75l.5 4.75m-12.5.5v12.75M21.25 8.5v12.75");
}

.n_jx8ebpc {
  d: path("M2.75 14.5h18.5V18H2.75z");
}

.oof2upb3i {
  cx: 12px;
  cy: 13px;
  r: 1.5px;
}

.szw-6_b5h {
  cx: 16px;
  cy: 13px;
  r: 1.5px;
}

.u-10n5mpy {
  cx: 8px;
  cy: 13px;
  r: 1.5px;
}

.x2cwu0gfd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
