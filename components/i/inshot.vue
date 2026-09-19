<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<circle class="c3f-hsbol"/><path class="aix2y_b0w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:inshot" /></template>
<style>
.aix2y_b0w {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M5.5 9.611h28.889a4.01 4.01 0 0 1 4 4v18.097m4.111 6.681H13.611a4.01 4.01 0 0 1-4-4v-18.2m0-6.578V5.5m28.778 32.889V42.5");
}

.c3f-hsbol {
  cx: 24px;
  cy: 24px;
  r: 7px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>
