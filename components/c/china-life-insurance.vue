<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="ynv8_vb_k"/><circle class="rmwop1a6h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:china-life-insurance" /></template>
<style>
.rmwop1a6h {
  cx: 35.177px;
  cy: 12.608px;
  r: 8.108px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.ynv8_vb_k {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M42.45 26.559A18.919 18.919 0 1 1 21.327 5.804");
}

</style>
