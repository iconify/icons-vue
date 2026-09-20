<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="ovttdqb7o"/><circle class="eth-ijbrs"/><path class="bpbt_tbio"/><path class="q-2z8rbcu"/><path class="utm_-wbvc"/><circle class="mf4cgib2r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:croc" /></template>
<style>
.bpbt_tbio {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M21.594 37.2a12.14 12.14 0 0 1-16.096-4.734a9.23 9.23 0 0 1 4.064-12.404l15.498-7.848");
}

.eth-ijbrs {
  cx: 27.736px;
  cy: 12.416px;
  r: 2.689px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.mf4cgib2r {
  cx: 27.736px;
  cy: 12.416px;
  r: 0.75px;
  fill: currentColor;
}

.ovttdqb7o {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m30.624 20.606l11.824-5.988a1.92 1.92 0 0 0 .845-2.579l-.393-.776a3.32 3.32 0 0 0-3.545-1.768l-9.345 1.49");
}

.q-2z8rbcu {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M21.594 37.2a1.405 1.405 0 1 0-1.27-2.506c-1.554.787-4.202 1.62-5.704-1.344a5.48 5.48 0 0 1-.375-3.697");
}

.utm_-wbvc {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m15.32 25.68l-.389-.768a1.677 1.677 0 0 0-2.253-.738a1.677 1.677 0 0 0-.739 2.254l1.16 2.29a1.83 1.83 0 0 0 2.457.805l1.36-.689l3.747-1.897a3.535 3.535 0 0 0-4.75-1.557Zm10.65-5.393l-.39-.768a1.677 1.677 0 0 0-2.252-.738a1.677 1.677 0 0 0-.739 2.253l1.16 2.291a1.83 1.83 0 0 0 2.457.805l1.36-.69l3.747-1.897a3.535 3.535 0 0 0-4.75-1.556Zm-1.89 3.497l-4.206 2.129m-9.207-6.41l-.289 1.704m3.185-3.171l-.288 1.704m3.185-3.171l-.288 1.704m3.185-3.171l-.289 1.704m3.185-3.171l-.288 1.704m9.022.459l2.63.669l1.017-2.516l2.629.669l1.018-2.516l2.632.668l1.019-2.517");
}

</style>
