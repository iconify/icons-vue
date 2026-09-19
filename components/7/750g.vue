<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<rect class="j3s9ivbxi"/><path class="n6m2vbcyn"/><rect class="fkb-81bzb"/><path class="j9fobbuut"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:750g" /></template>
<style>
.fkb-81bzb {
  width: 7.651px;
  height: 11.549px;
  x: 30.349px;
  y: 18.226px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  rx: 3.825px;
  ry: 3.825px;
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

.j9fobbuut {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M20.463 28.8c.797.668 1.571.974 3.504.974h.332a3.24 3.24 0 0 0 3.238-3.237h0a3.24 3.24 0 0 0-3.238-3.238h-3.836v-5.073h7.074");
}

.n6m2vbcyn {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m11.437 29.774l6.214-11.548H10");
}

</style>
