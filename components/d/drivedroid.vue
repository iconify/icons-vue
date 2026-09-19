<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<circle class="b0qezeb0b"/><circle class="p7-vlcccv"/><path class="s-wbygbug"/><path class="z5n7icb_u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:drivedroid" /></template>
<style>
.b0qezeb0b {
  cx: 24.21px;
  cy: 39.53px;
  r: 3.97px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.p7-vlcccv {
  cx: 12.47px;
  cy: 17.93px;
  r: 3.97px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.s-wbygbug {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m24.21 4.5l-4.38 7.58h8.76zm8.18 9.87h7.11v7.11h-7.11zm-8.18 21.19V12.08");
}

.z5n7icb_u {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M35.95 21.48v5.92H12.47v-5.5");
}

</style>
