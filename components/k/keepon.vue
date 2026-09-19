<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="lm-p6tbzh"/><circle class="d93m67bim"/><path class="fuggexcoi"/><circle class="d_6bc5iye"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:keepon" /></template>
<style>
.d_6bc5iye {
  cx: 24px;
  cy: 17.91px;
  r: 10.65px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.d93m67bim {
  cx: 23.95px;
  cy: 17.88px;
  r: 1.23px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.fuggexcoi {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M23.95 16.65v-4.97m1.04 6.87l6.02 3.85");
}

.lm-p6tbzh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M24 4.5a13.51 13.51 0 0 0-13.41 13.41c0 8 7.32 11.07 7.32 15.24v1.21h12.18v-1.21c0-4.15 7.32-7.2 7.32-15.24A13.51 13.51 0 0 0 24 4.5m-6.09 29.86h12.18v4.57H17.91Zm0 4.57h12.18v4.57H17.91Z");
}

</style>
