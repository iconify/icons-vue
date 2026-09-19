<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="o5e-bmb1s"/><circle class="e4qcezehi"/><path class="phu5ilzrr"/><circle class="m25byb48a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:connect-you" /></template>
<style>
.e4qcezehi {
  cx: 34.235px;
  cy: 22.893px;
  r: 4.975px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.m25byb48a {
  cx: 20.168px;
  cy: 15.809px;
  r: 6.848px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.o5e-bmb1s {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M24.97 39.04v-3.719c2.974-2.974 5.467-3.918 9.265-3.918h0c3.798 0 6.29.944 9.265 3.918v3.719z");
}

.phu5ilzrr {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M24.97 39.04H4.5v-6.289c5.03-5.03 9.245-6.625 15.668-6.625h0c5.765 0 9.752 1.286 14.146 5.188");
}

</style>
