<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<rect class="j3s9ivbxi"/><path class="p-v86c20j"/><circle class="h6unt-cma"/><path class="ckytwnbwm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:64" /></template>
<style>
.ckytwnbwm {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M22.172 18.823c-.756-.99-1.908-1.67-3.817-1.67h-.318a4.537 4.537 0 0 0-4.537 4.536v4.622");
}

.h6unt-cma {
  cx: 18.037px;
  cy: 26.311px;
  r: 4.537px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
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

.p-v86c20j {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m32.778 30.848l-.001-13.696l-7.35 9.2H34.5");
}

</style>
