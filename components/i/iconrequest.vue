<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="shvymh__q"/><path class="w_fkjzvxp"/><path class="kflrljb8l"/><path class="h6pykabqn"/><circle class="p9-58zr-m"/><circle class="xgj9z2bnv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:iconrequest" /></template>
<style>
.h6pykabqn {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M23.058 24.14h2.255v1.967h.819a1.263 1.263 0 0 1 1.25 1.281v3.082l-2.24 2.322a1.223 1.223 0 0 1-1.767 0l-2.36-2.423v-2.98a1.263 1.263 0 0 1 1.25-1.282h.793Zm-12.019-2.914h25.75a1.515 1.515 0 0 0 1.476-1.512v-1.9a11.6 11.6 0 0 0-2.686-7.292l2.015-1.992a2.394 2.394 0 0 0 0-3.326a2.32 2.32 0 0 0-3.335.006l-2.007 1.992c-5.448-3.468-11.003-3.73-16.735 0L13.584 5.24a2.29 2.29 0 0 0-3.338-.003c-1.434 1.244-.218 3.112-.004 3.323l2.007 1.977a11.22 11.22 0 0 0-2.723 7.276v1.9a1.51 1.51 0 0 0 1.513 1.513");
}

.kflrljb8l {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m26.562 31.32l3.294 5.84l.232 2.41l-1.883-1.357l-3.032-5.453m-1.892-.064l-3.01 5.413l-1.885 1.556l.156-2.525l3.362-5.859");
}

.p9-58zr-m {
  cx: 17.252px;
  cy: 15.532px;
  r: 2.153px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.shvymh__q {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M36.79 21.226a1.6 1.6 0 0 1 1.669 1.341l.02 6.55a14.38 14.38 0 0 1-7.192 12.456A14.373 14.373 0 0 1 9.724 29.021v-6.454a1.183 1.183 0 0 1 1.315-1.34");
}

.w_fkjzvxp {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M31.024 31.407A5.22 5.22 0 0 1 27.83 36a7.53 7.53 0 0 1-6.387 0");
}

.xgj9z2bnv {
  cx: 30.612px;
  cy: 15.532px;
  r: 2.153px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>
