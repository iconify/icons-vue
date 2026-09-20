<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<rect class="j3s9ivbxi"/><path class="p41bnqwzq"/><circle class="cb5ia3ccv"/><circle class="p-4fqhbev"/><circle class="nxrc1ybwp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:hardoff" /></template>
<style>
.cb5ia3ccv {
  cx: 22.931px;
  cy: 13.792px;
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

.nxrc1ybwp {
  cx: 27.476px;
  cy: 12.193px;
  r: 0.75px;
  fill: currentColor;
}

.p-4fqhbev {
  cx: 32.021px;
  cy: 13.792px;
  r: 0.75px;
  fill: currentColor;
}

.p41bnqwzq {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M24.89 24.624v-8h2.619c1.48 0 2.681 1.203 2.681 2.687s-1.2 2.686-2.681 2.686H24.89m2.62.001l2.62 2.624m-19.393-7.998v8m5.3-8v8m-5.3-4.015h5.3m15.926 4.015v-8h1.8a3.5 3.5 0 0 1 3.5 3.5v1a3.5 3.5 0 0 1-3.5 3.5zm-9.728-2.65h-3.544m-.882 2.65l2.65-8l2.65 8m-.459 6.999h2.6m1.4-4h-4v8m6.049-4h2.6m1.401-4h-4v8m-10.749-7.999za2.65 2.65 0 0 1 2.65 2.65v2.7a2.65 2.65 0 1 1-5.3 0v-2.7a2.65 2.65 0 0 1 2.65-2.65");
}

</style>
