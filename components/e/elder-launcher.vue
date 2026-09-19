<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="haedycbbf"/><circle class="xwy2_2ykj"/><path class="us4h8o8cd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:elder-launcher" /></template>
<style>
.haedycbbf {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M42.5 19.42a13.673 13.673 0 0 1-13.673 13.672h0A13.673 13.673 0 0 1 15.154 19.42h0A13.673 13.673 0 0 1 28.827 5.746h0A13.673 13.673 0 0 1 42.5 19.42m-6.405 22.834H6.047m22.741 0v-9.162M8.535 42.254V25.16");
}

.us4h8o8cd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M6.1 33.638v-6.982m4.87 6.982v-6.982m27.984-7.236A10.127 10.127 0 1 1 28.826 9.292a10.127 10.127 0 0 1 10.126 10.126");
}

.xwy2_2ykj {
  cx: 8.535px;
  cy: 20.006px;
  r: 3.035px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>
