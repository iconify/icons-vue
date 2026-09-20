<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="m6vr5p7of"/><path class="v2k0_xskf"/><path class="is2vlfytl"/><path class="sn3n0eket"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:day-to-day-expenses" /></template>
<style>
.is2vlfytl {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M24.649 17.04h10.71a2.78 2.78 0 0 1 2.786 2.773v8.01a2.78 2.78 0 0 1-2.774 2.785H24.649a2.78 2.78 0 0 1-2.786-2.773v-8.01a2.78 2.78 0 0 1 2.774-2.786z");
}

.m6vr5p7of {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M9.386 9.648A20.4 20.4 0 0 1 24 3.503c11.294 0 20.45 9.155 20.45 20.449S35.294 44.402 24 44.402S3.55 35.246 3.55 23.952c0-3.946 1.119-7.631 3.055-10.756");
}

.sn3n0eket {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M35.85 30.562v2.75a2.78 2.78 0 0 1-2.773 2.787H14.41a2.78 2.78 0 0 1-2.786-2.774V14.592a2.78 2.78 0 0 1 2.774-2.786h18.665a2.78 2.78 0 0 1 2.785 2.774v2.504M1.45 16.563l5.395-3.952l.725 6.648");
}

.v2k0_xskf {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M30.819 23.824a2.193 2.193 0 0 1-4.387 0c0-1.211.982-2.193 2.193-2.193h.001c1.211 0 2.193.982 2.193 2.193");
}

</style>
