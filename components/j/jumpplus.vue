<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="gw4zcwb-x"/><path class="qkrbmubok"/><circle class="c-rujkq1b"/><circle class="we58b9jhj"/><ellipse class="rvouwy12b"/><path class="swb18wy8q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:jumpplus" /></template>
<style>
.c-rujkq1b {
  cx: 12.781px;
  cy: 20.156px;
  r: 0.75px;
  fill: currentColor;
}

.gw4zcwb-x {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M9.021 39.422C.93 31.564.287 18.79 7.548 10.159c7.26-8.63 19.957-10.183 29.084-3.556c9.126 6.628 11.58 19.18 5.62 28.756c-5.96 9.575-18.307 12.917-28.283 7.655M9.02 39.422L6.06 44.55l7.907-1.534m6.006-5.844h8.053M24 33.146v8.052M5.084 20.178h5.282m13.004 0h5.512m3.688 0h6.03M5.035 23.086h5.33");
}

.qkrbmubok {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M4.99 28.904h5.376l2.464-2.51V22.73m10.59 6.174h5.462l2.465-2.51v-3.311m2.416 5.821h5.613l2.465-2.51v-2.65m-26.769 1.499h5.34l.924 1.034l-1.31 1.156m-4.022-3.457l1.667 5.081");
}

.rvouwy12b {
  cx: 41.844px;
  cy: 20.365px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  rx: 1.428px;
  ry: 1.454px;
}

.swb18wy8q {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M19.53 9.317v3.481s.022.692-.685.692h-.358m-1.445-3.43s.157 1.77-.698 2.635m5.265-2.715l.692 2.61m-.793 1.67s-.93 1.389-4.498 1.389m9.404-6.332s-.184 1.479-1.176 2.058m.917-.953h4.57m.055 2.135h-4.659v1.528m-1.057.586h6.217m-2.553-4.193v5.288");
}

.we58b9jhj {
  cx: 14.586px;
  cy: 20.156px;
  r: 0.75px;
  fill: currentColor;
}

</style>
