<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="mm8hg9beb"/><path class="pn1tgib9d"/><g class="y9tr6bcfx"><circle class="u9d_sw9aa"/><circle class="kobviqr1t"/><circle class="lddv11bqv"/><circle class="ttltizbnk"/></g><g class="y9tr6bcfx"><path class="ljcxydgdt"/><path class="p44a491jb"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:busmap" /></template>
<style>
.kobviqr1t {
  cx: 32.222px;
  cy: 28.497px;
  r: 4.111px;
}

.lddv11bqv {
  cx: 15.778px;
  cy: 28.497px;
  r: 1.542px;
}

.ljcxydgdt {
  d: path("M19.889 28.497h8.222m-16.444 0H7.556c-1.028 0-2.056-1.028-2.056-2.056V9.997c0-1.028 1.028-2.056 2.056-2.056h32.889c1.027 0 2.055 1.028 2.055 2.055v16.445c0 1.028-1.028 2.056-2.056 2.056h-4.11");
}

.mm8hg9beb {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m17.346 36.657l-2.082-.452l.252 2.233");
}

.p44a491jb {
  d: path("m5.5 20.274l8.222-2.57H38.39v-6.68H5.5m8.222 0v6.68m9.25.001v-6.68m9.25 6.68v-6.68");
}

.pn1tgib9d {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M15.264 36.205c3.083 5.139 14.389 5.139 17.472 0");
}

.ttltizbnk {
  cx: 32.222px;
  cy: 28.497px;
  r: 1.542px;
}

.u9d_sw9aa {
  cx: 15.778px;
  cy: 28.497px;
  r: 4.111px;
}

.y9tr6bcfx {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>
