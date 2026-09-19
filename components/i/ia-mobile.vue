<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<rect class="j3s9ivbxi"/><circle class="x7sv6uboq"/><path class="orvvz2bqr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:ia-mobile" /></template>
<style>
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

.orvvz2bqr {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m15.396 20.927l-1.074 12.529m17.821-6.265h-8.366m-2.61 6.265l7.877-18.913l4.634 18.913");
}

.x7sv6uboq {
  cx: 15.893px;
  cy: 15.135px;
  r: 0.75px;
  fill: currentColor;
}

</style>
