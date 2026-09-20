<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="e3hpd9bmc"/><circle class="cpk0fnbgt"/><path class="x2ixl2b_h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:gasflow" /></template>
<style>
.cpk0fnbgt {
  cx: 24px;
  cy: 24px;
  r: 21.5px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.e3hpd9bmc {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M24 9.61a9.15 9.15 0 0 1 9.14 9.14A9.15 9.15 0 0 1 24 27.88a9.14 9.14 0 1 1 0-18.27m4.57 4.57l-5.82 3.32l-.2 2.69l2.7-.19z");
}

.x2ixl2b_h {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M4.07 32.04h39.86");
}

</style>
