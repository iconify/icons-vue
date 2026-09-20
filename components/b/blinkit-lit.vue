<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<circle class="vfj5hsb5s"/><circle class="w6vae-7hg"/><path class="yepmahbot"/><path class="difmc613e"/><path class="d49kl-byt"/><path class="irsq1ly8d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:blinkit-lit" /></template>
<style>
.d49kl-byt {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M44 37a7 7 0 1 1-14 0a7 7 0 0 1 14 0");
}

.difmc613e {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M31.077 41H8c-2.216 0-4-1.784-4-4V8c0-2.216 1.784-4 4-4h29c2.216 0 4 1.784 4 4v23.204");
}

.irsq1ly8d {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M34.767 35.118c-.114.831-.144 1.549.404 1.93c-.015-1.67 1.475-1.979 1.435-3.442c-.01-.346-.123-.739-.484-1.22c1.136-.318 2.017.49 2.384 1.486c.587 1.589-.12 2.148.157 2.968c.152.451.976.507 1.213-.089c1.139 1.307.668 3.141-.376 4.003c-1.554 1.283-3.478 1.225-4.902.02s-1.653-4.5.169-5.656");
}

.vfj5hsb5s {
  cx: 17.657px;
  cy: 17.545px;
  r: 0.75px;
  fill: currentColor;
}

.w6vae-7hg {
  cx: 33.34px;
  cy: 17.545px;
  r: 0.75px;
  fill: currentColor;
}

.yepmahbot {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M17.657 20.845v6.596m15.683-6.596v6.596M14.004 17.67v8.55c0 .733.489 1.221 1.222 1.221h.366m21.026-8.55v7.329c0 .733.489 1.221 1.222 1.221h.366m-2.931-6.596h2.687m-13.485 6.596v-4.03a2.45 2.45 0 0 0-2.443-2.444a2.45 2.45 0 0 0-2.442 2.443m0 4.031v-6.596M7.206 23.288a2.45 2.45 0 0 1 2.443-2.443a2.45 2.45 0 0 1 2.443 2.443v1.588A2.45 2.45 0 0 1 9.65 27.32a2.45 2.45 0 0 1-2.443-2.443m-.001 2.564V17.67m19.184-.123v9.894m0-2.076l4.396-4.52m-2.931 3.054l3.42 3.42");
}

</style>
