<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="udh0qtbft"/><path class="bxjg96btz"/><circle class="nkgzsibjx"/><path class="wc8xy4bwx"/><rect class="j3s9ivbxi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:kavli-ipmu" /></template>
<style>
.bxjg96btz {
  fill: currentColor;
  d: path("M16.87 9.974a.75.75 0 1 1-1.5 0a.75.75 0 0 1 1.5 0m21.164 15.403a.75.75 0 1 1-1.5 0a.75.75 0 0 1 1.5 0m-9.329-2.925a.75.75 0 1 1-1.5 0a.75.75 0 0 1 1.5 0");
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

.nkgzsibjx {
  cx: 26.953px;
  cy: 19.585px;
  r: 0.75px;
  fill: currentColor;
}

.udh0qtbft {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M11.474 26.957c0 .714-.579 1.293-1.293 1.293h0a1.293 1.293 0 0 1-1.293-1.294h0a1.293 1.293 0 0 1 2.586 0m19.665 3.437v5.3c0 1.5 1.2 2.7 2.6 2.7s2.6-1.2 2.6-2.7v-5.3m-15.353 8v-8l4 8l4-8v8m-15.452 0v-8h2.6c1.5 0 2.7 1.2 2.7 2.7s-1.2 2.7-2.7 2.7h-2.6m-3.353-5.4v8m-1.2-8h2.4m-2.4 8h2.4");
}

.wc8xy4bwx {
  fill: currentColor;
  d: path("M37.127 11.346a.75.75 0 0 1-1.5 0a.75.75 0 0 1 1.5 0m-4.035-.462a.75.75 0 0 1-1.5 0a.75.75 0 0 1 1.5 0");
}

</style>
