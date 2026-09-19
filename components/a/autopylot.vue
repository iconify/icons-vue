<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="u_nj_5qso"/><path class="y7f04tm7r"/><path class="ksyy-4bxo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:autopylot" /></template>
<style>
.ksyy-4bxo {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M17.059 21.284a9.353 9.353 0 1 0 13.489 12.962");
}

.u_nj_5qso {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M29.153 28.167A9.353 9.353 0 1 0 15.797 16.12");
}

.y7f04tm7r {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M24 25.37a9.25 9.25 0 1 0-12 8.834m12-8.834a9.25 9.25 0 1 0 12-8.834");
}

</style>
