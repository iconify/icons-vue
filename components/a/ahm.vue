<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<rect class="cim_5vaxq"/><path class="mb69qetzm"/><path class="p7nfk8baj"/><circle class="urpifhb6k"/><path class="zrotd0bcw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:ahm" /></template>
<style>
.cim_5vaxq {
  width: 33.7px;
  height: 26.7px;
  x: 4.9px;
  y: 10.65px;
  fill: none;
  stroke: currentColor;
  stroke-dasharray: 3.8 2;
  stroke-linecap: round;
  stroke-linejoin: round;
  rx: 3.5px;
  ry: 3.5px;
}

.mb69qetzm {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M23.9 24.85c0-1.3 1.1-2.4 2.4-2.4s2.4 1.1 2.4 2.4v3.9m-4.8-6.2v6.2");
}

.p7nfk8baj {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M28.6 24.85c0-1.3 1.1-2.4 2.4-2.4s2.4 1.1 2.4 2.4v3.9m-16.5-9.4v9.4m0-3.9c0-1.3 1.1-2.4 2.4-2.4s2.4 1.1 2.4 2.4v3.9m-6.9-2.3c0 1.3-1.1 2.4-2.4 2.4s-2.4-1.1-2.4-2.4v-1.5c0-1.3 1.1-2.4 2.4-2.4s2.4 1.1 2.4 2.4m0 3.8v-6.2");
}

.urpifhb6k {
  cx: 41.8px;
  cy: 33.75px;
  r: 1.3px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.zrotd0bcw {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m38.6 30.15l2.4 2.6m1.5-7.7l-3.9 5.1");
}

</style>
