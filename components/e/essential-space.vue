<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<circle class="wkxw5hbfm"/><path class="adc_10n7k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:essential-space" /></template>
<style>
.adc_10n7k {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m21 3.305l-13.424 7.75a6 6 0 0 0-3 5.195v15.5a6 6 0 0 0 3 5.195L21 44.695a6 6 0 0 0 6 0l13.424-7.75a6 6 0 0 0 3-5.195v-15.5a6 6 0 0 0-3-5.195L27 3.305a6 6 0 0 0-6 0m3 12.123V8.5m0 31v-6.928m7.424-12.857l6-3.464m-26.847 15.5l6-3.464m-.001-8.571l-6-3.464m26.847 15.5l-6-3.464");
}

.wkxw5hbfm {
  cx: 24px;
  cy: 24px;
  r: 3px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>
