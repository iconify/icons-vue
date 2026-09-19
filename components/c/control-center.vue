<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<circle class="r8yxwf_hn"/><circle class="jfowm4b8o"/><circle class="j_oxt4sqe"/><circle class="aj98gcg0r"/><path class="cl3rdzbcq"/><path class="f8dkjo73u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:control-center" /></template>
<style>
.aj98gcg0r {
  cx: 34.406px;
  cy: 34.406px;
  r: 8.094px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.cl3rdzbcq {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M34.406 16.594v-6m-3 3h6m-6 20.812h6M11.119 11.119c-.633.633-1.025 1.508-1.025 2.475s.392 1.841 1.025 2.475s1.508 1.025 2.475 1.025s1.841-.392 2.475-1.025s1.025-1.509 1.025-2.475s-.392-1.842-1.025-2.475m-2.475 1.467V9.652m2.545 25.802c-.651-.652-1.551-1.055-2.545-1.055s-1.894.403-2.545 1.054m3.634 1.454c-.58-.582-1.598-.582-2.179 0M9.594 34c1.067-1.069 2.487-1.657 4-1.657s2.932.588 4 1.658");
}

.f8dkjo73u {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M16.139 35.454c-.651-.652-1.551-1.055-2.545-1.055s-1.894.403-2.545 1.054");
}

.j_oxt4sqe {
  cx: 13.594px;
  cy: 34.406px;
  r: 8.094px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.jfowm4b8o {
  cx: 34.406px;
  cy: 13.594px;
  r: 8.094px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.r8yxwf_hn {
  cx: 13.594px;
  cy: 13.594px;
  r: 8.094px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>
