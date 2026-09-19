<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<rect class="j3s9ivbxi"/><path class="e0pi_tb_m"/><path class="wec8arb3o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:dnsnet" /></template>
<style>
.e0pi_tb_m {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M24 42.5s-5.518-8.942 0-18.5s0-18.5 0-18.5m-8 37s-5.518-8.942 0-18.5s0-18.5 0-18.5m16 37s-5.518-8.942 0-18.5s0-18.5 0-18.5");
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

.wec8arb3o {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M5.5 25.5S11.669 17.774 24 24s18.5-1.5 18.5-1.5M5.5 15s6.169-7.726 18.5-1.5S42.5 12 42.5 12m-37 24s6.169-7.726 18.5-1.5S42.5 33 42.5 33");
}

</style>
