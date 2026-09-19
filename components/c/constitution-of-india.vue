<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="wnmeb41rx"/><circle class="q521xyb9l"/><path class="irgxxbtkb"/><rect class="j3s9ivbxi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:constitution-of-india" /></template>
<style>
.irgxxbtkb {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M28.328 22.735v5.941M35 26.475c0 1.21-.958 2.2-2.13 2.2s-2.13-.99-2.13-2.2v-1.43c0-1.21.959-2.2 2.13-2.2s2.13.99 2.13 2.2m0 3.631v-5.941m-15.546 5.941v-3.63c0-1.211-.959-2.201-2.13-2.201s-2.13.99-2.13 2.2m0 3.631v-5.941m10.723 2.2c0-1.21-.959-2.2-2.13-2.2s-2.13.99-2.13 2.2v1.43c0 1.21.959 2.2 2.13 2.2s2.13-.99 2.13-2.2m0 2.311v-8.802");
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

.q521xyb9l {
  cx: 28.328px;
  cy: 20.094px;
  r: 0.75px;
  fill: currentColor;
}

.wnmeb41rx {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M13 19.875v8.801");
}

</style>
