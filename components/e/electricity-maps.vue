<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<circle class="o9s-fbc4k"/><circle class="nlnia8bqg"/><circle class="zkl-ofbax"/><circle class="tu1gbp68w"/><circle class="ej2hozjot"/><circle class="d9y0fyb5r"/><circle class="i_-fhgc4k"/><circle class="hgx-kk2hg"/><path class="s0jzfsbya"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:electricity-maps" /></template>
<style>
.d9y0fyb5r {
  cx: 7.068px;
  cy: 24px;
  r: 1.568px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.ej2hozjot {
  cx: 40.932px;
  cy: 7.068px;
  r: 1.568px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.hgx-kk2hg {
  cx: 7.068px;
  cy: 7.068px;
  r: 1.568px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.i_-fhgc4k {
  cx: 24px;
  cy: 7.068px;
  r: 1.568px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.nlnia8bqg {
  cx: 24px;
  cy: 40.932px;
  r: 1.568px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.o9s-fbc4k {
  cx: 40.932px;
  cy: 40.932px;
  r: 1.568px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.s0jzfsbya {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m24.612 13.067l-10.51 13.128l8.816.425l.22 8.031L33.71 21.255l-8.69.063z");
}

.tu1gbp68w {
  cx: 40.932px;
  cy: 24px;
  r: 1.568px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.zkl-ofbax {
  cx: 7.068px;
  cy: 40.932px;
  r: 1.568px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>
