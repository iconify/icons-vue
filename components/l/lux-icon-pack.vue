<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<rect class="jz8nrkbfv"/><circle class="xyhhj5b6q"/><circle class="ocdj7abqo"/><circle class="jwrz54b_z"/><circle class="i4i2iac6m"/><circle class="tbqc6tb1l"/><circle class="eokpm4bio"/><circle class="ll1-3kw5m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:lux-icon-pack" /></template>
<style>
.eokpm4bio {
  cx: 10.5px;
  cy: 37.5px;
  r: 5px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.i4i2iac6m {
  cx: 37.5px;
  cy: 23.974px;
  r: 5px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.jwrz54b_z {
  cx: 37.5px;
  cy: 10.5px;
  r: 5px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.jz8nrkbfv {
  width: 10px;
  height: 23.5px;
  x: 5.5px;
  y: 5.5px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  rx: 5px;
  ry: 5px;
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

.ocdj7abqo {
  cx: 24px;
  cy: 23.974px;
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
