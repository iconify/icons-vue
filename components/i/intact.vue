<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="d4o2c2hpw"/><circle class="dvupgoj0v"/><path class="hb1zqhboj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:intact" /></template>
<style>
.d4o2c2hpw {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M33.696 27.196c-.325.65-1.083 1.083-1.842 1.083a2.173 2.173 0 0 1-2.167-2.167v-1.408c0-1.192.975-2.167 2.167-2.167c.758 0 1.517.434 1.842 1.084m-6.176 2.546c0 1.191-.974 2.166-2.166 2.166s-2.167-.975-2.167-2.166v-1.409c0-1.191.975-2.166 2.167-2.166s2.167.975 2.167 2.166m0 3.575v-5.85m-7.367-1.733v6.5c0 .65.433 1.083 1.083 1.083h.326m-2.601-5.85h2.384m15.167-1.787v6.5c0 .65.433 1.083 1.083 1.083h.325m-2.6-5.85h2.383");
}

.dvupgoj0v {
  cx: 10.296px;
  cy: 19.883px;
  r: 0.75px;
  fill: currentColor;
}

.hb1zqhboj {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M10.296 22.483v5.85m7.042 0v-3.575c0-1.191-.976-2.166-2.167-2.166s-2.167.975-2.167 2.166m0 3.575v-5.85m25.079-9.316H43.5v21.666h-5.417M9.917 13.167H4.5v21.666h5.417");
}

</style>
