<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="dq1hr0b4f"/><path class="rcug-dbeb"/><path class="qnzbnrcot"/><path class="e6psnq_9m"/><rect transform="rotate(-45 24.04 23.994)" class="m6_4q7ela"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:linex" /></template>
<style>
.dq1hr0b4f {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m27.153 10.969l5.352-5.347l10.032 10.03l-15.384 15.386");
}

.e6psnq_9m {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m11.013 20.884l-5.346-5.352L15.697 5.5l15.386 15.384");
}

.m6_4q7ela {
  width: 5.561px;
  height: 5.561px;
  x: 21.26px;
  y: 21.213px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  rx: 0.948px;
}

.qnzbnrcot {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m20.847 37.066l-5.352 5.347l-10.032-10.03l15.384-15.387");
}

.rcug-dbeb {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m37.056 27.116l5.347 5.352L32.373 42.5L16.986 27.116");
}

</style>
