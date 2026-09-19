<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<circle class="cpk0fnbgt"/><circle class="b-bn85b1a"/><circle class="b29nl0gjt"/><circle class="sq363xb3s"/><circle class="h_u7t_hpf"/><path class="lq51y3b-y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:arsvechkarev-vault" /></template>
<style>
.b-bn85b1a {
  cx: 17.5px;
  cy: 17.5px;
  r: 2.5px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.b29nl0gjt {
  cx: 30.5px;
  cy: 17.5px;
  r: 2.5px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.cpk0fnbgt {
  cx: 24px;
  cy: 24px;
  r: 21.5px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.h_u7t_hpf {
  cx: 30.5px;
  cy: 30.5px;
  r: 2.5px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.lq51y3b-y {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M19.27 15.73L31.24 3.76m1.03 15.51l11.97 11.97m-15.51 1.03L16.76 44.24m-1.03-15.51L3.76 16.76");
}

.sq363xb3s {
  cx: 17.5px;
  cy: 30.5px;
  r: 2.5px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>
