<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="z8hftfb7i"/><circle class="isw9ao04t"/><path class="hgvggi20o"/><circle class="nargkvbdv"/><path class="ur-o8yb8g"/><circle class="cpk0fnbgt"/><circle class="zyr_y6bpm"/><circle class="yfx5g2bhd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:lookofdisapproval" /></template>
<style>
.cpk0fnbgt {
  cx: 24px;
  cy: 24px;
  r: 21.5px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.hgvggi20o {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  d: path("M6.534 19.534h9.958A1.91 1.91 0 0 0 17.51 16");
}

.isw9ao04t {
  cx: 12.581px;
  cy: 25.151px;
  r: 5.617px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-miterlimit: 10;
}

.nargkvbdv {
  cx: 35.647px;
  cy: 25.151px;
  r: 5.617px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-miterlimit: 10;
}

.ur-o8yb8g {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  d: path("M29.6 19.534h9.958A1.91 1.91 0 0 0 40.576 16");
}

.yfx5g2bhd {
  cx: 35.647px;
  cy: 25.151px;
  r: 0.75px;
  fill: currentColor;
}

.z8hftfb7i {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  d: path("M18.934 32.448h10.132");
}

.zyr_y6bpm {
  cx: 12.581px;
  cy: 25.151px;
  r: 0.75px;
  fill: currentColor;
}

</style>
