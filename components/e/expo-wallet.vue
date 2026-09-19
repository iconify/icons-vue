<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="o2q4vxi_k"/><circle class="ecg0a8bsl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:expo-wallet" /></template>
<style>
.ecg0a8bsl {
  cx: 36.086px;
  cy: 16.607px;
  r: 1.319px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.o2q4vxi_k {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m16.7 11.312l5.694 9.92m3.09 5.379l5.744 10.118M4.764 15.902L16.7 36.681m14.555-25.37l-14.554 25.37m26.535-20.864L31.256 36.68m-.001-25.369l9.068-.04m-23.623.04l-9.023.045m32.646-.085c1.078.02 2.076.58 2.66 1.492s.68 2.057.253 3.054M7.677 11.356a3.23 3.23 0 0 0-2.66 1.492a3.28 3.28 0 0 0-.253 3.054");
}

</style>
