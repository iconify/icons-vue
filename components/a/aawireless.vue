<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<circle class="aamg6lbyb"/><path class="gi6zg7o7y"/><circle class="o6cohabic"/><path class="wg50_8koe"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:aawireless" /></template>
<style>
.aamg6lbyb {
  cx: 17.458px;
  cy: 33.956px;
  r: 9.544px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.gi6zg7o7y {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M27.001 33.956V43.5");
}

.o6cohabic {
  cx: 22.667px;
  cy: 25.76px;
  r: 9.544px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.wg50_8koe {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M32.211 25.76v9.544m2.318-18.096a9.546 9.546 0 0 0-10.236-6.644m15.793 4.515C38.293 7.659 30.823 3.097 23.403 4.89");
}

</style>
