<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<circle class="p5ogr3bka"/><path class="oxc29ebbk"/><path class="a4zsstb0h"/><g class="y9tr6bcfx"><path class="cw1i-m0bv"/><path class="uamrelrmf"/></g><path class="kucehob3b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:lysn" /></template>
<style>
.a4zsstb0h {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M13.676 18.751v8h4");
}

.cw1i-m0bv {
  d: path("M23.069 24.751v2.7a2 2 0 0 1-2 2a2 2 0 0 1-1.414-.586");
}

.kucehob3b {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M25.052 26.304c.365.307.759.447 1.645.447h.448c.73 0 1.322-.593 1.322-1.325s-.592-1.325-1.322-1.325h-.897c-.73 0-1.322-.593-1.322-1.325s.592-1.325 1.322-1.325h.448c.886 0 1.28.14 1.645.447m5.983 4.853v-3.3a2 2 0 1 0-4 0m0 3.3v-5.3");
}

.oxc29ebbk {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M21.74 45.5c-10.553 0-19.109-8.555-19.109-19.109s8.556-19.109 19.11-19.109s19.11 8.556 19.11 19.11V45.5z");
}

.p5ogr3bka {
  cx: 26.233px;
  cy: 21.635px;
  r: 19.136px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.uamrelrmf {
  d: path("M23.069 21.451v3.3a2 2 0 1 1-4 0v-3.3");
}

.y9tr6bcfx {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>
