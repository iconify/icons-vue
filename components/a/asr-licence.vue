<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="dfpxp_bbq"/><circle class="gp-b1_b4h"/><path class="khplb_bdd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:asr-licence" /></template>
<style>
.dfpxp_bbq {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M32.959 43.55a21.484 21.484 0 1 1 10.59-10.586");
}

.gp-b1_b4h {
  cx: 38px;
  cy: 38px;
  r: 7.5px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.khplb_bdd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M31.222 34.811a12.997 12.997 0 1 1 3.577-3.57m2.633 2.902l-1.361 7.714h3.858");
}

</style>
