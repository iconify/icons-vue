<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<rect class="md3m4eaas"/><path class="iyv2l5bma"/><circle class="zovy1bcny"/><path class="wh7sxgbfc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:lineage-radio" /></template>
<style>
.iyv2l5bma {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M38.721 12.238V9.762");
}

.md3m4eaas {
  width: 39px;
  height: 26px;
  x: 4.5px;
  y: 12.238px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  rx: 2.622px;
}

.wh7sxgbfc {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M33.53 15.896a9.744 9.744 0 0 1-.69 18.86l-2.08-6.335a3.184 3.184 0 0 0 .341-6.35Zm-.218 11.239l5.576 3.469");
}

.zovy1bcny {
  cx: 17.108px;
  cy: 25.238px;
  r: 9.741px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>
