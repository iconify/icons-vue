<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="i9clfwm2k"/><path class="anbg612tp"/><circle class="h0mbmrbuv"/><circle class="w7uj33b1f"/><path class="b pkgl-73ct"/><path class="dlgjv-bvm"/><circle class="pcwaflbfr"/><circle class="l6wlltube"/><path class="b kinn6dbri"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:chess-clock" /></template>
<style>
.anbg612tp {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M12.226 36.142c.6.5 1.1.7 2.4.7h.3c1.4 0 2.6-1.2 2.6-2.6s-1.2-2.6-2.6-2.6h-2.7v-2.8h5.3");
}

.dlgjv-bvm {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M5.5 24h37m-6.726-12.142c-.6-.5-1.1-.7-2.4-.7h-.3c-1.4 0-2.6 1.2-2.6 2.6s1.2 2.6 2.6 2.6h2.7v2.8h-5.3");
}

.h0mbmrbuv {
  cx: 20.142px;
  cy: 35.639px;
  r: 0.75px;
  fill: currentColor;
}

.i9clfwm2k {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M38.5 5.5h-29a4 4 0 0 0-4 4v29a4 4 0 0 0 4 4h29a4 4 0 0 0 4-4v-29a4 4 0 0 0-4-4");
}

.kinn6dbri {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M25.242 13.63c0-1.5-1.2-2.7-2.7-2.7s-2.6 1.2-2.6 2.7v2.7c0 1.5 1.2 2.7 2.6 2.7s2.7-1.2 2.7-2.7zm-7.716 0c0-1.5-1.2-2.7-2.7-2.7s-2.6 1.2-2.6 2.7v2.7c0 1.5 1.2 2.7 2.6 2.7s2.7-1.2 2.7-2.7z");
}

.l6wlltube {
  cx: 27.858px;
  cy: 17.661px;
  r: 0.75px;
  fill: currentColor;
}

.pcwaflbfr {
  cx: 27.858px;
  cy: 12.361px;
  r: 0.75px;
  fill: currentColor;
}

.pkgl-73ct {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M22.758 34.369c0 1.5 1.2 2.7 2.7 2.7s2.6-1.2 2.6-2.7v-2.7c0-1.5-1.2-2.7-2.6-2.7s-2.7 1.2-2.7 2.7zm7.716 0c0 1.5 1.2 2.7 2.7 2.7s2.6-1.2 2.6-2.7v-2.7c0-1.5-1.2-2.7-2.6-2.7s-2.7 1.2-2.7 2.7z");
}

.w7uj33b1f {
  cx: 20.142px;
  cy: 30.339px;
  r: 0.75px;
  fill: currentColor;
}

</style>
