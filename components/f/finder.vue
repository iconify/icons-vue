<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<rect class="sd2g05nnv"/><path class="mekntibai"/><circle class="z2kyr8bya"/><circle class="ckxq4x-jj"/><circle class="uwa5--n1r"/><circle class="wa1mr8i8e"/><circle class="s791d_b8u"/><circle class="yesedpbwf"/><circle class="r16b11boe"/><circle class="h9vki-boq"/><circle class="fjcnsdb0u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:finder" /></template>
<style>
.ckxq4x-jj {
  cx: 24px;
  cy: 31.61px;
  r: 0.75px;
  fill: currentColor;
}

.fjcnsdb0u {
  cx: 19.62px;
  cy: 40.37px;
  r: 0.75px;
  fill: currentColor;
}

.h9vki-boq {
  cx: 19.62px;
  cy: 35.99px;
  r: 0.75px;
  fill: currentColor;
}

.mekntibai {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M28.81 13.64v-3.62m-10.69 6.79h11.76v11.76H18.12zm5.36-9.64a6.61 6.61 0 0 1 5.3-2.68h0a6.63 6.63 0 0 1 5.31 2.68m-8 1.72a3.23 3.23 0 0 1 5.31 0");
}

.r16b11boe {
  cx: 28.38px;
  cy: 40.37px;
  r: 0.75px;
  fill: currentColor;
}

.s791d_b8u {
  cx: 24px;
  cy: 40.37px;
  r: 0.75px;
  fill: currentColor;
}

.sd2g05nnv {
  width: 18.09px;
  height: 29.85px;
  x: 14.96px;
  y: 13.64px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  rx: 2px;
}

.uwa5--n1r {
  cx: 28.38px;
  cy: 31.61px;
  r: 0.75px;
  fill: currentColor;
}

.wa1mr8i8e {
  cx: 24px;
  cy: 35.99px;
  r: 0.75px;
  fill: currentColor;
}

.yesedpbwf {
  cx: 28.38px;
  cy: 35.99px;
  r: 0.75px;
  fill: currentColor;
}

.z2kyr8bya {
  cx: 19.62px;
  cy: 31.61px;
  r: 0.75px;
  fill: currentColor;
}

</style>
