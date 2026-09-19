<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<rect class="j3s9ivbxi"/><circle class="s1m9pwbta"/><path class="ybdc0jgsb"/><circle class="i7woh20-z"/><path class="shhqp1_yc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:iliad" /></template>
<style>
.i7woh20-z {
  cx: 20.427px;
  cy: 19.768px;
  r: 0.75px;
  fill: currentColor;
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

.s1m9pwbta {
  cx: 13.34px;
  cy: 19.768px;
  r: 0.75px;
  fill: currentColor;
}

.shhqp1_yc {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M20.427 22.709v6.363m-4.25-9.604v8.404a1.2 1.2 0 0 0 1.2 1.2h.36m10.211-2.401a2.4 2.4 0 0 1-2.4 2.401h0a2.4 2.4 0 0 1-2.402-2.4V25.11a2.4 2.4 0 0 1 2.401-2.4h0a2.4 2.4 0 0 1 2.401 2.4m0 3.962v-6.363M35.5 25.11a2.4 2.4 0 0 0-2.401-2.4h0a2.4 2.4 0 0 0-2.401 2.4v1.561a2.4 2.4 0 0 0 2.4 2.401h0a2.4 2.4 0 0 0 2.402-2.4m0 2.4v-9.604");
}

.ybdc0jgsb {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M13.34 22.709v6.363");
}

</style>
