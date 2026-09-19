<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="kb3fg6dwe"/><circle class="ulff-ty2m"/><circle class="qzz2pwbuc"/><circle class="vrui_9ujd"/><circle class="boe79qjro"/><circle class="fvd-t06-t"/><circle class="sn7zuo60x"/><path class="pl6oz1bnh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:arcticons-material-you" /></template>
<style>
.boe79qjro {
  cx: 39.93px;
  cy: 33.2px;
  r: 3.11px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.fvd-t06-t {
  cx: 24px;
  cy: 42.39px;
  r: 3.11px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.kb3fg6dwe {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m24 10.84l-11.4 6.58v13.16L24 37.16l11.4-6.58V17.42z");
}

.pl6oz1bnh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m12.6 30.58l-1.84 1.06M24 37.16v2.12m0-28.44V8.71m11.4 21.87l1.84 1.06M35.4 17.42l1.84-1.06M12.6 17.42l-1.84-1.06m7.4 4.348L24 24.08m0 6.743V24.08m5.84-3.372L24 24.08");
}

.qzz2pwbuc {
  cx: 24px;
  cy: 5.61px;
  r: 3.11px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.sn7zuo60x {
  cx: 8.07px;
  cy: 33.2px;
  r: 3.11px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.ulff-ty2m {
  cx: 8.07px;
  cy: 14.8px;
  r: 3.11px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.vrui_9ujd {
  cx: 39.93px;
  cy: 14.8px;
  r: 3.11px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>
