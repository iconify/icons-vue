<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="o7yd34bgc"/><circle class="tl44kwbwv"/><circle class="enrl1qy0v"/><circle class="pztsnbbid"/><circle class="fc_2kzbiw"/><circle class="tbldexb8v"/><path class="pqcyxvb_c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:disciplined" /></template>
<style>
.enrl1qy0v {
  cx: 18.3px;
  cy: 31.4px;
  r: 3.7px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.fc_2kzbiw {
  cx: 20.3px;
  cy: 16.6px;
  r: 3.7px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.o7yd34bgc {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M9.2 5.5H24c10.217 0 18.5 8.283 18.5 18.5S34.217 42.5 24 42.5H9.5");
}

.pqcyxvb_c {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M9.2 12.9h11.102m-.002 7.4h-8.098m6.098 7.4h-6.102m6.102 7.4H9.198");
}

.pztsnbbid {
  cx: 12.2px;
  cy: 24px;
  r: 3.7px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.tbldexb8v {
  cx: 9.2px;
  cy: 9.2px;
  r: 3.7px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.tl44kwbwv {
  cx: 9.2px;
  cy: 38.8px;
  r: 3.7px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>
