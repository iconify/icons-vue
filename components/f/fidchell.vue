<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<circle class="ccnl2vb0e"/><circle class="f-jm3__vu"/><circle class="yp1q3cc0q"/><circle class="eor460bar"/><circle class="cpk0fnbgt"/><path class="i3m9ad4_d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:fidchell" /></template>
<style>
.ccnl2vb0e {
  cx: 24px;
  cy: 24px;
  r: 4.72px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.cpk0fnbgt {
  cx: 24px;
  cy: 24px;
  r: 21.5px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.eor460bar {
  cx: 24px;
  cy: 24px;
  r: 17.415px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.f-jm3__vu {
  cx: 24px;
  cy: 24px;
  r: 12.695px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.i3m9ad4_d {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M24 2.537v19.317zm-10.151 2.84l6.175 11.104zm20.86.192l-6.265 10.86zM9.393 8.69l2.597 2.525zm29.76.05l-2.468 3.368zM5.481 13.373l11.186 6.37zm37.292.115L32.01 20.395zM2.537 24h19.317zm23.61 0h19.317zM24 26.146v18.78zm-7.61 1.966L5.437 34.535zm14.586.474l11.023 5.827zm-11.315 2.65l-5.902 10.91zm8.791.056l6.376 11.132zm8.26 5.096l2.466 2.301zm-25.236.06l-2.5 2.602z");
}

.yp1q3cc0q {
  cx: 24px;
  cy: 24px;
  r: 8.329px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>
