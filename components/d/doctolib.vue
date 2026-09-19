<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="wz64ey1-d"/><path class="lrw44hiik"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:doctolib" /></template>
<style>
.lrw44hiik {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M17.288 6.027c9.294-.908 20.824-1.537 24.108 6.08s1.048 19.077-2.166 23.62s-10.46 7.448-17.4 6.638c-9.573-1.118-16.845-4.659-16.841-12.858a8.64 8.64 0 0 1 1.892-5.062");
}

.wz64ey1-d {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M28.888 11.548a120.4 120.4 0 0 0-4.89 20.964");
}

</style>
