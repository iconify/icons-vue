<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<circle class="q1h_2fupv"/><path class="uwpj62bbt"/><path class="dx92epbvm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:black-pie-icon-pack" /></template>
<style>
.dx92epbvm {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M19.58 21.962a6.7 6.7 0 0 1-3.741 1.132a6.7 6.7 0 0 1-5.402-2.728a6.67 6.67 0 0 1-1.337-4.01a6.743 6.743 0 0 1 6.739-6.75c1.584 0 3.04.55 4.193 1.467m6.114 16.667a9.04 9.04 0 0 0-1.995 5.682a9.069 9.069 0 1 0 18.134 0c0-3.46-1.94-6.48-4.808-8.01");
}

.q1h_2fupv {
  cx: 29.833px;
  cy: 16.926px;
  r: 11.426px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.uwpj62bbt {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M10.437 20.366a11.4 11.4 0 0 0-4.722 9.25c0 6.318 5.11 11.429 11.417 11.429a11.4 11.4 0 0 0 8.086-3.343");
}

</style>
