<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="jdeiuwett"/><path class="y0_bm_b9h"/><ellipse class="x8wviyb-t"/><path class="ewtzz8bfn"/><ellipse class="ril79cbgy"/><path class="e1nepac_g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:gymtrainer" /></template>
<style>
.e1nepac_g {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M7.583 21.595h1.844c.554 0 1.002 1.077 1.002 2.405s-.449 2.405-1.002 2.405H7.583m8.977-4.81h19.003c.554 0 1.002 1.077 1.002 2.405s-.449 2.405-1.002 2.405H16.56");
}

.ewtzz8bfn {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M8.647 14.048h3.704c2.29 0 4.147 4.456 4.147 9.952s-1.857 9.952-4.147 9.952H8.647");
}

.jdeiuwett {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M31.625 26.406c.444 4.338 2.08 7.543 4.023 7.543c2.288 0 4.151-4.457 4.151-9.949s-1.863-9.949-4.15-9.949c-1.943 0-3.58 3.205-4.024 7.543");
}

.ril79cbgy {
  cx: 7.583px;
  cy: 24px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  rx: 1.002px;
  ry: 2.405px;
}

.x8wviyb-t {
  cx: 8.647px;
  cy: 24px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  rx: 4.147px;
  ry: 9.952px;
}

.y0_bm_b9h {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M35.649 14.048h3.704c2.29 0 4.147 4.456 4.147 9.952s-1.857 9.952-4.147 9.952H35.65");
}

</style>
