<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="hzpqnlmob"/><path class="mf5lw433o"/><rect transform="matrix(-1 0 0 -1 51.457 58.74)" class="d0ojfbbie"/><circle class="fh2s3t1yr"/><path class="rz50ilbdp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:eu-login-mobile" /></template>
<style>
.d0ojfbbie {
  width: 4.292px;
  height: 5.687px;
  x: 23.583px;
  y: 26.526px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  rx: 2.146px;
  ry: 2.146px;
}

.fh2s3t1yr {
  cx: 30.073px;
  cy: 23.897px;
  r: 0.75px;
  fill: currentColor;
}

.hzpqnlmob {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M9.5 5.5h29a4 4 0 0 1 4 4v29a4 4 0 0 1-4 4h-29a4 4 0 0 1-4-4v-29a4 4 0 0 1 4-4");
}

.mf5lw433o {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M24.53 12.89v5.74a2.843 2.843 0 1 0 5.687 0v-5.74m-12.434 4.292h2.798m1.494 4.292h-4.292V12.89h4.292M11.5 23.629v8.584h4.292m12.083-5.687v6.438a2.146 2.146 0 0 1-2.146 2.146a2.14 2.14 0 0 1-1.518-.628");
}

.rz50ilbdp {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M30.073 26.526v5.687m6.427 0v-3.54a2.146 2.146 0 1 0-4.292 0m0 3.54v-5.687m-14.995 2.146a2.146 2.146 0 0 1 4.292 0v1.395a2.146 2.146 0 0 1-4.292 0z");
}

</style>
