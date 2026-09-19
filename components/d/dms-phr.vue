<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="g2wj9jbhp"/><path class="s9jo8j2gd"/><path class="jri4lt1hj"/><path class="ch0-i7bbv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:dms-phr" /></template>
<style>
.ch0-i7bbv {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M34.814 19.745a2.875 2.875 0 0 1-2.875 2.875h0a2.875 2.875 0 0 1-2.875-2.875h0a2.875 2.875 0 0 1 2.875-2.875h0a2.875 2.875 0 0 1 2.875 2.875");
}

.g2wj9jbhp {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M9.5 5.5h29c2.216 0 4 1.784 4 4v29c0 2.216-1.784 4-4 4h-29c-2.216 0-4-1.784-4-4v-29c0-2.216 1.784-4 4-4");
}

.jri4lt1hj {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M10.75 20.2v-5.934h27.043v9.34m-24.891-4.67H26.45m-1.022 2h1.022");
}

.s9jo8j2gd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M5.5 20.28h18.95c.243 0 .565.057.675.273l1.394 2.769c.135.266.52.364.819.364H42.5");
}

</style>
