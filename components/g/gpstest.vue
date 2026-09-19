<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="b-z3omb_k"/><g class="y9tr6bcfx"><path class="kx1vyj5ad"/><path class="hp-b2jbid"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:gpstest" /></template>
<style>
.b-z3omb_k {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m5.5 41.06l9.1-12L21.26 37l9.1-11.8L42.5 41.06Z");
}

.hp-b2jbid {
  d: path("M11.57 6.94a5.81 5.81 0 0 1-5.81 5.8v-5.8Z");
}

.kx1vyj5ad {
  d: path("M17.37 6.94A11.61 11.61 0 0 1 5.76 18.55V6.94Z");
}

.y9tr6bcfx {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>
