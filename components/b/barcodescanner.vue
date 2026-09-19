<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="gcb0-wbvt"/><circle class="pib4krsit"/><path class="m3aqw4r9g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:barcodescanner" /></template>
<style>
.gcb0-wbvt {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M16.184 26.159H7.5v12.94h12.94v-3.617m-9.152-5.535h5.411v5.411h-5.411zm9.155-11.717V7.5H7.503v12.94h10.68m-6.893-9.15h5.412v5.412H11.29zm24.175 9.152H39.1V7.502H26.16v8.686m3.788-4.899h5.411v5.412h-5.411z");
}

.m3aqw4r9g {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m34.5 34.5l10 9.999");
}

.pib4krsit {
  cx: 26.854px;
  cy: 26.853px;
  r: 10.588px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>
