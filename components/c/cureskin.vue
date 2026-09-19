<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="sv38ogbzn"/><circle class="u8kdebxej"/><path class="qj554fbra"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:cureskin" /></template>
<style>
.qj554fbra {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M30.5 30.5a6.5 6.5 0 1 1 0-13H37a6.5 6.5 0 1 1 0 13z");
}

.sv38ogbzn {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M11 30.5a6.5 6.5 0 1 1 0-13z");
}

.u8kdebxej {
  cx: 17.5px;
  cy: 24px;
  r: 6.5px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>
