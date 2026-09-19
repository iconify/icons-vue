<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<circle class="cpk0fnbgt"/><circle class="iajvjdbqy"/><circle class="n5djjmb_n"/><circle class="m0nq7qbdh"/><circle class="r_rymylrv"/><circle class="hzu81vgjb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:kruidvat" /></template>
<style>
.cpk0fnbgt {
  cx: 24px;
  cy: 24px;
  r: 21.5px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.hzu81vgjb {
  cx: 28.976px;
  cy: 36.26px;
  r: 3.65px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.iajvjdbqy {
  cx: 11.498px;
  cy: 24px;
  r: 3.65px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.m0nq7qbdh {
  cx: 28.976px;
  cy: 11.74px;
  r: 3.65px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.n5djjmb_n {
  cx: 20.237px;
  cy: 17.87px;
  r: 3.65px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.r_rymylrv {
  cx: 20.237px;
  cy: 30.13px;
  r: 3.65px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>
