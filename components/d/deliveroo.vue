<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="e-1u53yqy"/><circle class="kl0-gnbkq"/><circle class="vc-tp9j2x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:deliveroo" /></template>
<style>
.e-1u53yqy {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m29.92 21.93l1.9-17.43l9.72 1.01l-2.45 25.7L33.5 43.5L9.25 38.7L6.46 26.74L20.65 24L17.3 9.19l9.38-1.9z");
}

.kl0-gnbkq {
  cx: 30.78px;
  cy: 30.34px;
  r: 2.68px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.vc-tp9j2x {
  cx: 22.87px;
  cy: 29.19px;
  r: 2.68px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>
