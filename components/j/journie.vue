<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="k4ggzbc4e"/><path class="zx2gpnzcj"/><path class="noe3bibaw"/><path class="f51_xpb7i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:journie" /></template>
<style>
.f51_xpb7i {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m28.136 25.132l-5.13 5.13l-5.128-5.13a7.253 7.253 0 1 1 10.258 0");
}

.k4ggzbc4e {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M34.21 10.784q.538.442 1.041.946c5.665 5.665 5.665 14.851 0 20.516L24.993 42.504l-1.985-1.985m-3.144-13.401a7.253 7.253 0 0 1 9.17-11.155");
}

.noe3bibaw {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M33.265 30.261L23.007 40.519L12.749 30.261c-5.665-5.665-5.665-14.851 0-20.516s14.85-5.665 20.516 0s5.665 14.851 0 20.516");
}

.zx2gpnzcj {
  fill: none;
  stroke: currentColor;
  stroke-miterlimit: 10;
  d: path("m23.007 30.261l-3.144-3.144");
}

</style>
