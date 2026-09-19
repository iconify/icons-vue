<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<circle class="cevajcy8s"/><path class="ufojl8r5y"/><path class="z-cenbcch"/><ellipse class="eyziufh1e"/><path class="qh7nvbbjj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:eausweise-check" /></template>
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

.qh7nvbbjj {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m35.661 34.2l1.207.999l1.799-3M11.443 20.412h10.504m0 4.937h-8.221");
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
