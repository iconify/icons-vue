<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<rect class="a91-rsmal"/><path class="ro6b1ac2l"/><rect class="oabb5_7ct"/><path class="tfya-vbne"/><circle class="r3ii5z6xs"/><circle class="i10kj_b7e"/><circle class="zvj3dvb8v"/><circle class="syr6kfb2i"/><circle class="pr-ka_b6b"/><circle class="eswi5xbcv"/><circle class="i5ctk292a"/><circle class="vutpw1t_g"/><circle class="wf_hqr1ub"/><circle class="vy-vsrc4h"/><path class="g_n4xlbfb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:keymapper" /></template>
<style>
.a91-rsmal {
  width: 22.576px;
  height: 22.576px;
  x: 19.674px;
  y: 5.814px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  rx: 2.509px;
}

.eswi5xbcv {
  cx: 35.979px;
  cy: 16.788px;
  r: 0.75px;
  fill: currentColor;
}

.g_n4xlbfb {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M14.03 39.678h5.017v-3.763l-2.509-2.508l-2.508 2.508Zm-5.644-5.644h3.762l2.509-2.509l-2.383-2.508H8.386Zm16.304 0h-3.762l-2.508-2.509l2.383-2.508h3.888ZM14.03 23.373h5.017v3.763l-2.509 2.508l-2.508-2.508Z");
}

.i10kj_b7e {
  cx: 28.453px;
  cy: 14.28px;
  r: 0.75px;
  fill: currentColor;
}

.i5ctk292a {
  cx: 33.47px;
  cy: 16.788px;
  r: 0.75px;
  fill: currentColor;
}

.oabb5_7ct {
  width: 17.559px;
  height: 10.034px;
  x: 22.182px;
  y: 12.085px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  rx: 1.254px;
}

.pr-ka_b6b {
  cx: 35.979px;
  cy: 14.28px;
  r: 0.75px;
  fill: currentColor;
}

.r3ii5z6xs {
  cx: 25.945px;
  cy: 14.28px;
  r: 0.75px;
  fill: currentColor;
}

.ro6b1ac2l {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M27.826 28.39v11.288a2.503 2.503 0 0 1-2.508 2.508H7.758a2.503 2.503 0 0 1-2.508-2.508v-17.56a2.503 2.503 0 0 1 2.508-2.508h11.916");
}

.syr6kfb2i {
  cx: 33.47px;
  cy: 14.28px;
  r: 0.75px;
  fill: currentColor;
}

.tfya-vbne {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M27.826 19.986h6.272");
}

.vutpw1t_g {
  cx: 30.962px;
  cy: 16.788px;
  r: 0.75px;
  fill: currentColor;
}

.vy-vsrc4h {
  cx: 25.945px;
  cy: 16.788px;
  r: 0.75px;
  fill: currentColor;
}

.wf_hqr1ub {
  cx: 28.453px;
  cy: 16.788px;
  r: 0.75px;
  fill: currentColor;
}

.zvj3dvb8v {
  cx: 30.962px;
  cy: 14.28px;
  r: 0.75px;
  fill: currentColor;
}

</style>
