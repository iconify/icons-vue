<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="bttipybdg"/><path class="prr2zvbfx"/><circle class="jnjbcabsb"/><path class="nyc-q043e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:abimobil" /></template>
<style>
.bttipybdg {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M10.118 21.743L5.5 23.703L24 31.55l18.5-7.849l-5.682-2.41m-26.272 4.654V40.49");
}

.jnjbcabsb {
  cx: 34.566px;
  cy: 8.26px;
  r: 0.75px;
  fill: currentColor;
}

.nyc-q043e {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M34.566 12.297v8.733");
}

.prr2zvbfx {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M33.53 27.631v10.087S27.286 40.24 24 40.24s-9.53-2.523-9.53-2.523v-9.972m4.92-11.081h-5.808m-1.439 4.366l4.343-13.182l4.343 13.182m3.591-5.437a3.287 3.287 0 0 1 3.278-3.296a3.287 3.287 0 0 1 3.278 3.296v2.142a3.287 3.287 0 0 1-3.278 3.296a3.287 3.287 0 0 1-3.278-3.296m0 3.295V7.848");
}

</style>
