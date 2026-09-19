<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="lfvnzzbdk"/><circle class="v6tf9864w"/><rect class="j3s9ivbxi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:bns" /></template>
<style>
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

.lfvnzzbdk {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M17.44 25.95A5.56 5.56 0 0 1 23 20.39h0a5.56 5.56 0 0 1 5.56 5.56v3.61A5.56 5.56 0 0 1 23 35.12h0a5.56 5.56 0 0 1-5.56-5.56m0 5.56V12.88");
}

.v6tf9864w {
  cx: 31.15px;
  cy: 35.12px;
  r: 0.75px;
  fill: currentColor;
}

</style>
