<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<rect class="xq-89_owi"/><circle class="e-q63-nsh"/><circle class="o6xj5ibwz"/><circle class="dluguhb0z"/><path class="g8i5sybtz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:d-payment" /></template>
<style>
.dluguhb0z {
  cx: 33px;
  cy: 32.094px;
  r: 2px;
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
}

.e-q63-nsh {
  cx: 24px;
  cy: 32.094px;
  r: 2px;
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
}

.g8i5sybtz {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M15.69 20.307c0-1.504-1.283-2.724-2.866-2.724s-2.866 1.22-2.866 2.724v1.77c0 1.504 1.283 2.724 2.866 2.724s2.866-1.219 2.866-2.724m0 2.725V13.906m11.451 6.542l1.009 3.655a.3.3 0 0 1-.289.38h-3.966a.31.31 0 0 1-.3-.383l1.992-8.145m-6.26 6.272a18.3 18.3 0 0 0 3.63-1.348m-3.61-3.223h3.752m-1.794-2.169v9.405m9.513-7.36v4.693c0 1.551.651 2.207 1.312 2.207c.578 0 1.025-.516 1.274-1.184m3.936-5.228c.303.83.661 2.445.661 4.477");
}

.o6xj5ibwz {
  cx: 15px;
  cy: 32.094px;
  r: 2px;
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
}

.xq-89_owi {
  width: 37px;
  height: 37px;
  x: 5.5px;
  y: 5.5px;
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  rx: 4px;
  ry: 4px;
}

</style>
