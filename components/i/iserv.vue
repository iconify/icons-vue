<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="i9clfwm2k"/><path class="b kbrfy5b1i"/><g class="b"><circle class="jicjy5bwf"/><path class="jad2l5bad"/></g><path class="b vfwkhxbvx"/><path class="mc4pg3zla"/><circle class="p06_0ms4c"/><circle class="g6fn7is0p"/><circle class="pdmfqtbke"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:iserv" /></template>
<style>
.g6fn7is0p {
  cx: 15.817px;
  cy: 28.828px;
  r: 0.75px;
  fill: currentColor;
}

.i9clfwm2k {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M38.5 5.5h-29a4 4 0 0 0-4 4v29a4 4 0 0 0 4 4h29a4 4 0 0 0 4-4v-29a4 4 0 0 0-4-4");
}

.jad2l5bad {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M13.296 21.572v5.3");
}

.jicjy5bwf {
  cx: 13.296px;
  cy: 19.172px;
  r: 0.75px;
  fill: currentColor;
}

.kbrfy5b1i {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m35.456 21.472l-2 5.3l-2-5.3m-4.159 2.15c0-1.1.9-2 2-2m-2 0v5.3");
}

.mc4pg3zla {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M24.827 25.772c-.3.6-1 1-1.7 1c-1.1 0-2-.9-2-2v-1.3c0-1.1.9-2 2-2s2 .9 2 2v.7h-4m-.5 4.628l14.83.056");
}

.p06_0ms4c {
  cx: 13.293px;
  cy: 28.828px;
  r: 0.75px;
  fill: currentColor;
}

.pdmfqtbke {
  cx: 18.34px;
  cy: 28.828px;
  r: 0.75px;
  fill: currentColor;
}

.vfwkhxbvx {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M15.657 26.472c.4.3.8.4 1.6.4h.4c.7 0 1.3-.6 1.3-1.3s-.6-1.3-1.3-1.3h-.9c-.7 0-1.3-.6-1.3-1.3s.6-1.3 1.3-1.3h.4c.9 0 1.3.1 1.6.4");
}

</style>
