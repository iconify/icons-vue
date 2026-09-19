<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<circle class="spf4edbmm"/><path class="sz7viybvr"/><path class="i7nn37bgl"/><path class="k0155bbhq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:carlcare" /></template>
<style>
.i7nn37bgl {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M17.9 28.092a8.025 8.025 0 0 0 15.731.063M10.758 15.377c-2.44-.85-5.147.457-5.998 2.896s.457 5.148 2.896 5.998a4.7 4.7 0 0 0 3.108-.002");
}

.k0155bbhq {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M23.337 19.824v5.654a2.614 2.614 0 0 0 5.227 0V15.115M43.5 24.244c-1 .239-2.072.25-3.02-.15a5.08 5.08 0 0 1-3.104-4.684v-6.24a5.083 5.083 0 0 1 5.083-5.083M28.564 19.035c0-2.17 2.368-3.918 4.686-3.918");
}

.spf4edbmm {
  cx: 18.627px;
  cy: 19.824px;
  r: 4.71px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.sz7viybvr {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M10.761 24.262a15 15 0 0 0-.013.628c0 8.297 6.726 15.023 15.024 15.023s15.023-6.726 15.023-15.023");
}

</style>
