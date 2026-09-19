<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="n-qww4upy"/><path class="bnpr2_bhs"/><path class="hcp82ertw"/><circle class="ji6nqbbxl"/><path class="dzxfdt_gj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:antennapod-alt" /></template>
<style>
.bnpr2_bhs {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M32.33 36.53a15 15 0 1 0-16.74-.06");
}

.dzxfdt_gj {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m23.27 26l-6.62 18.2M24.73 26l6.62 18.2");
}

.hcp82ertw {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M30 30.14a8.6 8.6 0 1 0-12.08-.07");
}

.ji6nqbbxl {
  cx: 24px;
  cy: 24px;
  r: 2.13px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.n-qww4upy {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M34.59 42.72a21.5 21.5 0 1 0-21.18 0");
}

</style>
