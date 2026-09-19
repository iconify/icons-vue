<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<circle class="xbggisbod"/><circle class="orgpwbc4o"/><circle class="mjfxfnl4m"/><circle class="gqe46hz5h"/><path class="be1zccbun"/><circle class="qc0kocbls"/><circle class="l6gmmibpx"/><path class="rclmf1b7k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:looop-denki" /></template>
<style>
.be1zccbun {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m13.568 13.441l-3.886 4.118A3 3 0 0 1 4.5 15.5v-7m17.318 4.941l-3.886 4.118m12.136-4.118l-3.886 4.118m12.136-4.118l-3.886 4.118M37.5 15.5v5m-33 5h11c-11 4.327-10.887 11.82-2.751 14");
}

.gqe46hz5h {
  cx: 15.75px;
  cy: 15.5px;
  r: 3px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.l6gmmibpx {
  cx: 17px;
  cy: 31.5px;
  r: 0.75px;
  fill: currentColor;
}

.mjfxfnl4m {
  cx: 24px;
  cy: 15.5px;
  r: 3px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.orgpwbc4o {
  cx: 32.25px;
  cy: 15.5px;
  r: 3px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.qc0kocbls {
  cx: 13.5px;
  cy: 31.5px;
  r: 0.75px;
  fill: currentColor;
}

.rclmf1b7k {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M25.083 25.5L17 39.5c6.156-10.662 9-7.925 9-2c0 4.116 3.927.858 5-1m2.5-5h10m-10-3h9m-5-3l4.5 9.66c-2.075-.542-8-1.984-8 1.84c0 1.38 1.545 2.5 3.5 2.5h4");
}

.xbggisbod {
  cx: 40.5px;
  cy: 15.5px;
  r: 3px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>
