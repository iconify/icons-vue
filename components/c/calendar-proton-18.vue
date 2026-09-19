<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="zyyfpuxxa"/><path class="pe530nb2s"/><path class="f6_7b22_l"/><path class="wtoegrbgv"/><path class="orx8z1bik"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:calendar-proton-18" /></template>
<style>
.f6_7b22_l {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M43.5 25.793v-13.93a4 4 0 0 0-4-4h-31a4 4 0 0 0-4 4v24.275a4 4 0 0 0 4 4");
}

.orx8z1bik {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M35.207 40.138V15.819a3.14 3.14 0 0 0-3.138-3.138H4.5");
}

.pe530nb2s {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M24.778 26.41a3.76 3.76 0 0 0 3.75-3.75h0a3.76 3.76 0 0 0-3.75-3.75h-2.437a3.76 3.76 0 0 0-3.75 3.75h0a3.76 3.76 0 0 0 3.75 3.75");
}

.wtoegrbgv {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M43.5 36.138V11.862a4 4 0 0 0-4-4h-31a4 4 0 0 0-4 4v24.276a4 4 0 0 0 4 4h31a4 4 0 0 0 4-4");
}

.zyyfpuxxa {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m11.179 20.972l3.75-2.062m0 0v15m9.849-7.5h-2.437a3.76 3.76 0 0 0-3.75 3.75h0a3.76 3.76 0 0 0 3.75 3.75h2.437a3.76 3.76 0 0 0 3.75-3.75h0a3.76 3.76 0 0 0-3.75-3.75");
}

</style>
