<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<rect class="h8l7_vmfm"/><path class="cwhj18bwi"/><circle class="w-01p2bet"/><path class="whzris7ae"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:join" /></template>
<style>
.cwhj18bwi {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M21.593 9.994h19.953M21.593 36.059h19.953M21.593 7.447H8.252a1.8 1.8 0 0 0-1.798 1.798v31.457A1.8 1.8 0 0 0 8.252 42.5H24.61a1.8 1.8 0 0 0 1.798-1.798M6.454 11.941h15.139M6.454 38.006h15.139");
}

.h8l7_vmfm {
  width: 19.953px;
  height: 35.053px;
  x: 21.593px;
  y: 5.5px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  rx: 1.798px;
}

.w-01p2bet {
  cx: 15.483px;
  cy: 25.187px;
  r: 1.895px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.whzris7ae {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M17.378 25.187h4.215m0-1.895h9.711m-3.082 3.347l3.347-3.347l-3.347-3.347");
}

</style>
