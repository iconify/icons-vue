<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="h6f0xpbru"/><path class="jw206wbdg"/><circle class="ac_0b5bmc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:krungsri-disales" /></template>
<style>
.ac_0b5bmc {
  cx: 38.965px;
  cy: 6.026px;
  r: 0.75px;
  fill: currentColor;
}

.h6f0xpbru {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M38.965 27.384c0 8.472-6.868 15.34-15.34 15.34s-15.34-6.868-15.34-15.34s6.869-15.34 15.34-15.34c8.473 0 15.34 6.868 15.34 15.34m0 0v-17.35");
}

.jw206wbdg {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M17.449 34.558v-6.666h-1.637l7.814-8l7.812 8h-1.636v6.667h-4.41v-3.24c0-1.013-.788-1.828-1.766-1.828s-1.766.815-1.766 1.829v3.239z");
}

</style>
