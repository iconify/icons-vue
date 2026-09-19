<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="kqprqnbzq"/><path class="faaks-bdo"/><circle class="gm6lq4bsz"/><path class="e4t09p28b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:idtech4aplusplus" /></template>
<style>
.e4t09p28b {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M17.849 14.192v4.737m5.363-2.949c0-.988-.8-1.788-1.787-1.788h0c-.988 0-1.788.8-1.788 1.788v1.162c0 .987.8 1.787 1.788 1.787h0c.987 0 1.787-.8 1.787-1.787m0 1.787v-7.15m11.997 17.538h2.098m-1.049-1.049v2.098m2.704-1.049h2.098m-1.049-1.049v2.098m.08-6.447h-3.913m-.969 2.925l2.926-8.831l2.925 8.831");
}

.faaks-bdo {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M21.503 37.162v-6.257l-3.358 4.203h4.145M10.098 22.012h4.144m-2.072 6.257v-6.257m14.023 0v6.257m4.145-6.257v6.257m-4.145-3.14h4.145m-5.897 1.041v.026a2.07 2.07 0 0 1-2.072 2.073h0a2.07 2.07 0 0 1-2.073-2.073v-2.111c0-1.145.928-2.073 2.073-2.073h0c1.144 0 2.072.928 2.072 2.073v.025m-8.444 1.031h2.039m1.089 3.128h-3.128v-6.257h3.128");
}

.gm6lq4bsz {
  cx: 17.849px;
  cy: 12.002px;
  r: 0.75px;
  fill: currentColor;
}

.kqprqnbzq {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M20.218 42.5c5.306 0 8.637-2.993 8.637-6.198c0-2.808 1.821-5.163 3.768-5.183l.865-18.282C33.81 6.754 23.914 5.5 20.218 5.5S6.625 6.754 6.948 12.837l.865 18.282c1.946.02 3.767 2.375 3.767 5.183c0 3.205 3.331 6.198 8.638 6.198");
}

</style>
