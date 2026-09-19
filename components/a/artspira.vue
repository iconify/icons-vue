<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="ezog9sbqy"/><circle class="h6g2l3wjm"/><path class="u_wb71bet"/><rect class="j3s9ivbxi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:artspira" /></template>
<style>
.ezog9sbqy {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M14.197 23.749c0-.67.587-1.257 1.257-1.257h0m-1.257 0v3.351M33.72 23.75c0-.67.586-1.257 1.257-1.257h0m-1.257 0v3.351");
}

.h6g2l3wjm {
  cx: 31.038px;
  cy: 20.9px;
  r: 0.419px;
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

.u_wb71bet {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M31.038 22.492v3.351m-9.635-.335c.251.168.502.251 1.005.251h.251a.84.84 0 0 0 .838-.837h0a.84.84 0 0 0-.837-.838h-.587a.84.84 0 0 1-.838-.838h0a.84.84 0 0 1 .838-.838h.251c.587 0 .838 0 1.006.252m-5.027-1.174v3.77a.66.66 0 0 0 .67.671h.168m-1.509-3.435h1.34M39.5 24.587c0 .67-.586 1.256-1.257 1.256h0c-.67 0-1.257-.586-1.257-1.257v-.837c0-.67.587-1.257 1.257-1.257h0c.67 0 1.257.586 1.257 1.257m0 2.01v-3.35m-13.49 2.178c0 .67.587 1.256 1.258 1.256h0c.67 0 1.256-.586 1.256-1.257v-.837c0-.67-.586-1.257-1.256-1.257h0c-.67 0-1.257.586-1.257 1.257m0-1.257v5.027m-14.746-3.351H9.087M8.5 25.76l1.676-5.028l1.675 5.027");
}

</style>
