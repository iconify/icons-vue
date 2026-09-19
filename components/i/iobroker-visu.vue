<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="s552fj_lo"/><path class="tga_r61jp"/><rect class="za38td8kg"/><circle class="b_qcqubpw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:iobroker-visu" /></template>
<style>
.b_qcqubpw {
  cx: 24px;
  cy: 14.228px;
  r: 0.75px;
  fill: currentColor;
}

.s552fj_lo {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M24 16.713v10.705M13.5 10.27h21v23.59h-21zm8.02 27.46h4.96");
}

.tga_r61jp {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M26.028 14.228c3.8 1.035 6.256 4.775 5.742 8.742c-.513 3.968-3.837 6.933-7.77 6.933s-7.257-2.966-7.77-6.933c-.514-3.967 1.942-7.707 5.741-8.742");
}

.za38td8kg {
  width: 29px;
  height: 39px;
  x: 9.414px;
  y: 4.124px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  rx: 5px;
  ry: 5px;
}

</style>
