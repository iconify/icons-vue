<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<circle class="qc5g_ys0l"/><path class="uopm3zbbt"/><path class="uo_ot598a"/><path class="i9clfwm2k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:lyfpay" /></template>
<style>
.i9clfwm2k {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M38.5 5.5h-29a4 4 0 0 0-4 4v29a4 4 0 0 0 4 4h29a4 4 0 0 0 4-4v-29a4 4 0 0 0-4-4");
}

.qc5g_ys0l {
  cx: 35.764px;
  cy: 28.537px;
  r: 0.75px;
  fill: currentColor;
}

.uo_ot598a {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M27.062 19.249v5.916a3.586 3.586 0 0 1-3.586 3.586h0a3.586 3.586 0 0 1-3.585-3.586V19.25m12.064 9.501V16.918a2.51 2.51 0 0 1 2.51-2.51h0c1.235 0 2.006.366 2.535 1.05m-7.171 3.791h5.02");
}

.uopm3zbbt {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M11 14.408v14.343h7.171m8.891-3.586v4.84a3.586 3.586 0 0 1-3.586 3.586h0c-.99 0-1.886-.4-2.535-1.05");
}

</style>
