<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="rr083gbra"/><path class="bw14j0brp"/><circle class="g-1p6kb1y"/><circle class="cyk1i2bhu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:hidedroid" /></template>
<style>
.bw14j0brp {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M5.5 25.663h37s-19.205-10.502-37 0m7.52-9.386h21.96L31.539 5.5L21.185 7.105L16.182 5.91Zm9.168 16.11a2.53 2.53 0 0 1 3.625 0");
}

.cyk1i2bhu {
  cx: 30.464px;
  cy: 32.387px;
  r: 4.652px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.g-1p6kb1y {
  cx: 17.536px;
  cy: 32.387px;
  r: 4.652px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.rr083gbra {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m15.58 21.628l-2.521-2.44a2.495 2.495 0 1 0-3.544 3.51l.337.332m.002 4.991a15.1 15.1 0 0 0-1.098 5.632V40.9a1.6 1.6 0 0 0 1.604 1.6h27.307a1.6 1.6 0 0 0 1.565-1.6v-7.247a15.1 15.1 0 0 0-1.062-5.612m-.46-4.576l.81-.798a2.492 2.492 0 1 0-3.537-3.51l-2.542 2.645");
}

</style>
