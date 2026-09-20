<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<circle class="sv4u8nh7q"/><path class="l-vny-b-z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:animecix" /></template>
<style>
.l-vny-b-z {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M40.98 36.328a2.52 2.52 0 0 1-2.014-1.002L25.444 17.434A1.8 1.8 0 0 0 24 16.715c-.573 0-1.1.263-1.445.72L9.035 35.326a2.52 2.52 0 0 1-3.533.492a2.52 2.52 0 0 1-.492-3.532l13.52-17.893A6.8 6.8 0 0 1 24 11.671c2.17 0 4.161.992 5.469 2.722l13.52 17.893a2.52 2.52 0 0 1-2.01 4.042Z");
}

.sv4u8nh7q {
  cx: 24px;
  cy: 30.52px;
  r: 3.286px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>
