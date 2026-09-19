<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<circle class="uob9racrf"/><path class="qd5h3b0tj"/><circle class="qf_qmdb8f"/><path class="enn7qbbny"/><rect class="j3s9ivbxi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:blinkit" /></template>
<style>
.enn7qbbny {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M34.84 22.345v6.596M15.504 19.17v8.55c0 .733.489 1.221 1.222 1.221h.366m21.026-8.55v7.329c0 .733.489 1.221 1.222 1.221h.366m-2.931-6.596h2.687m-13.485 6.596v-4.03a2.45 2.45 0 0 0-2.443-2.444h0a2.45 2.45 0 0 0-2.442 2.443m0 4.031v-6.596M8.706 24.788a2.45 2.45 0 0 1 2.443-2.443h0a2.45 2.45 0 0 1 2.443 2.443v1.588a2.45 2.45 0 0 1-2.443 2.443h0a2.45 2.45 0 0 1-2.443-2.443m0 2.565V19.17m19.183-.123v9.894m0-2.076l4.397-4.52m-2.931 3.054l3.42 3.42");
}

.j3s9ivbxi {
  width: 37px;
  height: 37px;
  x: 5.5px;
  y: 5.5px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  rx: 4px;
  ry: 4px;
}

.qd5h3b0tj {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M19.157 22.345v6.596");
}

.qf_qmdb8f {
  cx: 34.84px;
  cy: 19.045px;
  r: 0.75px;
  fill: currentColor;
}

.uob9racrf {
  cx: 19.157px;
  cy: 19.045px;
  r: 0.75px;
  fill: currentColor;
}

</style>
