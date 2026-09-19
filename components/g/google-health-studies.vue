<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<circle class="mn5ahgb-w"/><circle class="xnl1pwabg"/><circle class="oiogrbbnf"/><circle class="u9a94tbxs"/><circle class="ishuxmn1p"/><circle class="oaji6vbrr"/><path class="jksk-8b8h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:google-health-studies" /></template>
<style>
.ishuxmn1p {
  cx: 39.3px;
  cy: 24px;
  r: 3.2px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.jksk-8b8h {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M32.16 19.538c-2.893.444-4.568 2.146-5.002 4.977a3.2 3.2 0 1 1-3.673-3.673c2.893-.445 4.567-2.146 5.002-4.978M16.86 19.538c-2.893.444-4.568 2.146-5.002 4.977a3.2 3.2 0 1 1-3.673-3.673c2.893-.445 4.567-2.146 5.002-4.978M32.16 34.838c-2.893.444-4.568 2.146-5.002 4.977a3.2 3.2 0 1 1-3.673-3.673c2.893-.445 4.567-2.146 5.002-4.978");
}

.mn5ahgb-w {
  cx: 31.65px;
  cy: 16.35px;
  r: 3.2px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.oaji6vbrr {
  cx: 24px;
  cy: 8.7px;
  r: 3.2px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.oiogrbbnf {
  cx: 31.65px;
  cy: 31.65px;
  r: 3.2px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.u9a94tbxs {
  cx: 16.35px;
  cy: 31.65px;
  r: 3.2px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.xnl1pwabg {
  cx: 16.35px;
  cy: 16.35px;
  r: 3.2px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>
