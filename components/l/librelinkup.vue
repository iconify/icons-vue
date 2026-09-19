<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<circle class="b_imih59o"/><circle class="uuw1ljcsx"/><circle class="fy92g0bzv"/><circle class="rn40q21yn"/><path class="k_57lofhl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:librelinkup" /></template>
<style>
.b_imih59o {
  cx: 13px;
  cy: 24px;
  r: 6.5px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.fy92g0bzv {
  cx: 37px;
  cy: 10px;
  r: 4.5px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.k_57lofhl {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m33.113 12.267l-14.498 8.457m0 6.551l14.498 8.457");
}

.rn40q21yn {
  cx: 37px;
  cy: 38px;
  r: 4.5px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.uuw1ljcsx {
  cx: 13px;
  cy: 24px;
  r: 1px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>
