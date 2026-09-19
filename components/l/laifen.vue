<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<rect class="j3s9ivbxi"/><path class="xskszjswh"/><circle class="kw2h7nbjx"/><path class="ezbbdf3yv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:laifen" /></template>
<style>
.ezbbdf3yv {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M17.984 25.1v2.729m-2.053-.113a2.693 2.693 0 1 1 2.05-2.622m-8.764-4.723s-.04 3.016-.04 4.601c.018 2.243 1.115 2.568 1.685 2.857");
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

.kw2h7nbjx {
  cx: 20.31px;
  cy: 20.421px;
  r: 0.75px;
  fill: currentColor;
}

.xskszjswh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M38.72 25.123v2.706m-5.385-2.707v2.707m0-2.684a2.694 2.694 0 0 1 5.385.002m-7.911-1.557l-2.038 1.548m2.466.56c-.167 1.073-1.124 1.888-2.165 2.077c-.776.16-1.63-.04-2.215-.585c-.874-.668-1.132-1.918-.789-2.932c.235-.753.824-1.392 1.578-1.643c1.112-.44 2.494-.02 3.163.974m-8.249 4.24s-.04-3.016-.04-4.6c.018-2.244 1.115-2.569 1.685-2.858m-1.628 3.631L24 23.96m-3.69-1.77v5.64");
}

</style>
