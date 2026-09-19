<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="xtrkibbtc"/><path class="qotp1mbph"/><path class="tczna2b5p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:kireipass" /></template>
<style>
.qotp1mbph {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M42.5 18.5a13 13 0 1 1-13-13");
}

.tczna2b5p {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M16.337 5.5L5.5 16.337v15.326L16.337 42.5h15.326L42.5 31.663V16.337L31.663 5.5zm20.244 4.919L16.5 29.5m8.726-8.291l10.149 17.579");
}

.xtrkibbtc {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M14.035 7.803A3.99 3.99 0 0 1 16.5 11.5v31");
}

</style>
