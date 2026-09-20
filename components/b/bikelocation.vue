<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="p53lf-qyg"/><circle class="vn16w925x"/><circle class="y6gt57bru"/><path class="cbe3fcu-g"/><path class="sn1q0zb0f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:bikelocation" /></template>
<style>
.cbe3fcu-g {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M29.12 13.06L23.72 20h-7.08l5.42-6.94z");
}

.p53lf-qyg {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M24 4.5zA15.93 15.93 0 0 0 8.08 20.42c0 6.22 3.93 11.9 7.8 16a52 52 0 0 0 7.73 6.78l.39.27l.39-.27a52 52 0 0 0 7.73-6.78c3.87-4.14 7.8-9.81 7.8-16A15.93 15.93 0 0 0 24 4.5");
}

.sn1q0zb0f {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m31.41 20l-3.14-9.52h-2.31m-4.42.38L23.72 20m-3.59-9.14h2.94M9.86 27.77h28.28");
}

.vn16w925x {
  cx: 31.41px;
  cy: 20px;
  r: 3.98px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.y6gt57bru {
  cx: 16.64px;
  cy: 20px;
  r: 3.98px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>
