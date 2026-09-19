<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="g5cgecc9k"/><circle class="h4tmbhbmm"/><path class="yqtoxcczo"/><circle class="eyn9wwbra"/><path class="jxzf2rc6x"/><circle class="o0igblbuy"/><path class="g3is4rimb"/><circle class="ii5k-89dz"/><path class="ybaq2mbvq"/><circle class="f0dqw6b7k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:caixa-enginyers" /></template>
<style>
.eyn9wwbra {
  cx: 40.077px;
  cy: 30.169px;
  r: 3.896px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.f0dqw6b7k {
  cx: 24.001px;
  cy: 24.001px;
  r: 2.085px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.g3is4rimb {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m18.653 27.687l-13.02 7.345c5.326 3.482 12.625-3.04 13.02-7.345m-.981-2.205L3.5 30.242c.976-6.287 10.707-7.347 14.17-4.76");
}

.g5cgecc9k {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m29.348 20.316l13.02-7.346c-5.326-3.482-12.625 3.04-13.02 7.345");
}

.h4tmbhbmm {
  cx: 30.186px;
  cy: 7.954px;
  r: 3.896px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.ii5k-89dz {
  cx: 7.925px;
  cy: 17.833px;
  r: 3.896px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.jxzf2rc6x {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m27.686 29.349l7.346 13.02c3.482-5.326-3.04-12.625-7.346-13.02m-2.204.981l4.76 14.171c-6.288-.976-7.347-10.707-4.76-14.17");
}

.o0igblbuy {
  cx: 17.833px;
  cy: 40.077px;
  r: 3.896px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.ybaq2mbvq {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M20.315 18.654L12.97 5.634c-3.482 5.325 3.041 12.624 7.346 13.02m2.204-.982L17.759 3.501c6.288.976 7.347 10.707 4.76 14.171");
}

.yqtoxcczo {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m30.33 22.52l14.17-4.76c-.975 6.287-10.707 7.347-14.17 4.76");
}

</style>
