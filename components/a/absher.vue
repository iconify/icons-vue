<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="ve4gwf00a"/><circle class="ccztkptlk"/><path class="ft5ab_1ig"/><circle class="d_4rh1byu"/><circle class="ruqkuac3g"/><circle class="bpv-blbja"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:absher" /></template>
<style>
.bpv-blbja {
  cx: 16.343px;
  cy: 13.669px;
  r: 1.362px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.ccztkptlk {
  cx: 25.644px;
  cy: 13.669px;
  r: 1.362px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.d_4rh1byu {
  cx: 30.295px;
  cy: 40.972px;
  r: 1.362px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.ft5ab_1ig {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M36.308 4.5a2.724 2.724 0 0 0-2.724 2.724h2.724z");
}

.ruqkuac3g {
  cx: 20.994px;
  cy: 13.669px;
  r: 1.362px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.ve4gwf00a {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M11.692 17.655V43.5m4.651-25.845v19.932m4.651-19.932v19.932m4.65-19.932v19.932m4.651-26.244v26.244m4.651-27.905v29.3");
}

</style>
