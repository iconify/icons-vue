<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<circle class="v8cxm8n7m"/><circle class="u7ye2infl"/><circle class="lrz7s9hqw"/><circle class="i9eoxlbhx"/><circle class="q5ay8ln6e"/><circle class="xbv2nbclp"/><circle class="txxib_npc"/><circle class="g5ft-tbjd"/><path class="ctn5ocbki"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:dots-and-co" /></template>
<style>
.ctn5ocbki {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m23.134 19.5l-4.619 8a1 1 0 0 0 .866 1.5h9.238a1 1 0 0 0 .866-1.5l-4.619-8a1 1 0 0 0-1.732 0");
}

.g5ft-tbjd {
  cx: 24px;
  cy: 38px;
  r: 4.5px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.i9eoxlbhx {
  cx: 10px;
  cy: 24px;
  r: 4.5px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.lrz7s9hqw {
  cx: 24px;
  cy: 10px;
  r: 4.5px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.q5ay8ln6e {
  cx: 38px;
  cy: 24px;
  r: 4.5px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.txxib_npc {
  cx: 38px;
  cy: 38px;
  r: 4.5px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.u7ye2infl {
  cx: 38px;
  cy: 10px;
  r: 4.5px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.v8cxm8n7m {
  cx: 10px;
  cy: 10px;
  r: 4.5px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.xbv2nbclp {
  cx: 10px;
  cy: 38px;
  r: 4.5px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>
