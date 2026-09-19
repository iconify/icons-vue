<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="s_4fbctlo"/><path class="evcadyfno"/><path class="g-0bfebdl"/><ellipse class="eeoa_gbpp"/><ellipse class="ti7q2ml9n"/><ellipse class="k3lblrepy"/><ellipse class="skoxn06vl"/><ellipse class="hrzyugb7d"/><ellipse class="pu6ft9b_m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:defendo" /></template>
<style>
.eeoa_gbpp {
  cx: 16.8px;
  cy: 8.66px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  rx: 1.08px;
  ry: 1.09px;
}

.evcadyfno {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m31.24 33.1l4.51-4.53V10.25M16.16 33.09l-3.82-3.79l-.08-14.72");
}

.g-0bfebdl {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M12.28 21.24h2.66l1.86-1.86V9.75");
}

.hrzyugb7d {
  cx: 35.74px;
  cy: 9.15px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  rx: 1.08px;
  ry: 1.09px;
}

.k3lblrepy {
  cx: 20.68px;
  cy: 21.79px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  rx: 1.08px;
  ry: 1.09px;
}

.pu6ft9b_m {
  cx: 30.78px;
  cy: 17.72px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  rx: 1.08px;
  ry: 1.09px;
}

.s_4fbctlo {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M15.24 43.49a9.66 9.66 0 0 1 2.41-11.93a9.5 9.5 0 0 1 12.09 0a9.66 9.66 0 0 1 2.4 11.93m-11.48-13.6v-7m6.07 7V6.68m0 18.32h2.51l1.55-1.57v-4.62");
}

.skoxn06vl {
  cx: 26.73px;
  cy: 5.59px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  rx: 1.08px;
  ry: 1.09px;
}

.ti7q2ml9n {
  cx: 12.26px;
  cy: 13.48px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  rx: 1.08px;
  ry: 1.09px;
}

</style>
