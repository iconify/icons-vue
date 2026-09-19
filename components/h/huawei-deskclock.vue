<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<circle class="i2un9doxs"/><path class="sxtsi3bto"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:huawei-deskclock" /></template>
<style>
.i2un9doxs {
  cx: 24px;
  cy: 26.63px;
  r: 16.87px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.sxtsi3bto {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M23.943 4.5v22.3m0 0l7.754 5.943m2.653 7.21l2.894 3.487m-23.14-3.147l-2.556 3.147M19.019 4.5h9.622");
}

</style>
