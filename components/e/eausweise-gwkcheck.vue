<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<circle class="q_u2smbio"/><path class="opjyxbvyg"/><circle class="cevajcy8s"/><path class="ufojl8r5y"/><path class="z-cenbcch"/><ellipse class="eyziufh1e"/><path class="m3y9qzyif"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:eausweise-gwkcheck" /></template>
<style>
.cevajcy8s {
  cx: 29.355px;
  cy: 19.872px;
  r: 2.47px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.eyziufh1e {
  cx: 37.164px;
  cy: 33.699px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  rx: 4.115px;
  ry: 4.127px;
}

.m3y9qzyif {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M11.443 20.412h10.504m0 4.937h-8.221");
}

.opjyxbvyg {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M37.401 33.964L38.59 35.3");
}

.q_u2smbio {
  cx: 36.651px;
  cy: 33.011px;
  r: 1.212px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.ufojl8r5y {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M24.828 28.515a4.526 4.526 0 0 1 9.052-.006v.006z");
}

.z-cenbcch {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m33.56 35.691l-23.457.025c-1.845-.039-3.382-.96-3.382-2.85V13.024c0-1.891 1.537-2.812 3.382-2.85l25.797.028s2.919 0 2.919 2.822v16.895");
}

</style>
