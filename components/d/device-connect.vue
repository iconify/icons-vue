<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<rect class="hmu4f3bvn"/><rect class="m1eg27b5i"/><rect class="sda0dt__s"/><path class="bsfcu07zb"/><path class="tyhlfibjp"/><path class="pv1syntlb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:device-connect" /></template>
<style>
.bsfcu07zb {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m25.026 5.5l2.217 2.018l-2.217 2.019");
}

.hmu4f3bvn {
  width: 10.268px;
  height: 18.475px;
  x: 30.179px;
  y: 5.644px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  rx: 1.022px;
}

.m1eg27b5i {
  width: 16.933px;
  height: 12.473px;
  x: 7.553px;
  y: 23.453px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  rx: 1.135px;
}

.pv1syntlb {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M18.95 20.268v-6.86a1.423 1.423 0 0 1 1.423-1.423h6.9");
}

.sda0dt__s {
  width: 16.918px;
  height: 4.275px;
  x: 7.561px;
  y: 38.225px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  rx: 1.105px;
}

.tyhlfibjp {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M14.194 20.54v-8.278a4.744 4.744 0 0 1 4.743-4.744h8.306M17.66 18.861l1.29 1.407l1.29-1.407");
}

</style>
