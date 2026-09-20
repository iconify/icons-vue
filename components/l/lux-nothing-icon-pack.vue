<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<circle class="ceu-4923b"/><circle class="xyhhj5b6q"/><circle class="smh8hwt4g"/><circle class="tbqc6tb1l"/><circle class="ll1-3kw5m"/><path class="eom_l4g3d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:lux-nothing-icon-pack" /></template>
<style>
.ceu-4923b {
  cx: 10.5px;
  cy: 10.5px;
  r: 5px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.eom_l4g3d {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M10.5 19za5 5 0 0 1 5 5v13.5a5 5 0 0 1-10 0V24a5 5 0 0 1 5-5m27-13.5za5 5 0 0 1 5 5V24a5 5 0 0 1-10 0V10.5a5 5 0 0 1 5-5");
}

.ll1-3kw5m {
  cx: 37.5px;
  cy: 37.5px;
  r: 5px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.smh8hwt4g {
  cx: 24px;
  cy: 24px;
  r: 5px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.tbqc6tb1l {
  cx: 24px;
  cy: 37.5px;
  r: 5px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.xyhhj5b6q {
  cx: 24px;
  cy: 10.5px;
  r: 5px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>
