<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<rect class="j3s9ivbxi"/><path class="qxv9c4b7w"/><circle class="dmqxq9l9v"/><path class="sxuop-dsf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:kaidee" /></template>
<style>
.dmqxq9l9v {
  cx: 20.754px;
  cy: 20.077px;
  r: 0.75px;
  fill: currentColor;
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

.qxv9c4b7w {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M9.5 19.834v7.769m.001-1.65l3.517-3.5m-2.398 2.386l2.765 2.753");
}

.sxuop-dsf {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M20.754 22.456v5.147m-2.069-1.943a1.942 1.942 0 1 1-3.885 0v-1.262a1.942 1.942 0 0 1 3.885 0m0 3.205v-5.147m13.679 4.167a1.942 1.942 0 0 1-3.63-.962v-1.263a1.942 1.942 0 0 1 3.885 0v.632h-3.885m9.511 1.593a1.942 1.942 0 0 1-3.63-.962v-1.263a1.942 1.942 0 0 1 3.885 0v.632h-3.885m-7.865-.632a1.942 1.942 0 0 0-3.885 0v1.263a1.942 1.942 0 0 0 3.885 0m0 1.942v-7.769");
}

</style>
