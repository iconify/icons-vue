<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<rect class="zw87d7c2p"/><rect class="yxvbn4bpx"/><rect class="skrv6eb-j"/><rect class="vjccqkbdj"/><rect class="dus5-cokv"/><path class="jge10pbrz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:chorus-pro" /></template>
<style>
.dus5-cokv {
  width: 10.226px;
  height: 10.226px;
  x: 20.736px;
  y: 24.098px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  rx: 1.54px;
  ry: 1.54px;
}

.jge10pbrz {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m25.343 16.109l1.241-3.033m3.946 20.773l2.646 1.714");
}

.skrv6eb-j {
  width: 7.676px;
  height: 7.676px;
  x: 33.176px;
  y: 34.825px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  rx: 1.156px;
  ry: 1.156px;
}

.vjccqkbdj {
  width: 7.676px;
  height: 7.676px;
  x: 7.148px;
  y: 11.7px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  rx: 1.156px;
  ry: 1.156px;
}

.yxvbn4bpx {
  width: 7.676px;
  height: 7.676px;
  x: 25.894px;
  y: 5.5px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  rx: 1.156px;
  ry: 1.156px;
}

.zw87d7c2p {
  width: 15.056px;
  height: 15.056px;
  x: 10.986px;
  y: 16.029px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  rx: 1.107px;
  ry: 1.107px;
}

</style>
