<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="mueoqibgb"/><path class="sz1ct2b2c"/><path class="xk51rnu1o"/><path class="p0dv5kb5c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:downwell" /></template>
<style>
.mueoqibgb {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M23.252 14.639h2.804v6.241h-2.804z");
}

.p0dv5kb5c {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M22.804 28.238h7.87v3.043h-7.87z");
}

.sz1ct2b2c {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M30.771 31.281v8.321H22.45v-2.08h-2.081v-3.161h-2.08V19.762h-3.043v-3.043H5v-5.278h10.246v2.08h3.043v-3.043h2.08v-2.08h13.145v6.241h-2.841v6.241h5.124v-2.081H43v5.005H30.673v4.434");
}

.xk51rnu1o {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M30.673 28.238h6.221v9.284h-3.043v-6.241h-3.08");
}

</style>
