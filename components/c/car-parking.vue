<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="lcvv66bju"/><path class="qg3in1ban"/><circle class="w53nakbdl"/><circle class="m6n3gsbty"/><path class="ybh0g2boo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:car-parking" /></template>
<style>
.lcvv66bju {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M32.53 27.943h2.2l-.238-2.321l-1.081-1.266l-8.031-.765L21.737 18h-8.162l-5.038 5.328l-4.43 1.107l-.607 2.901l.633.607h3.534m5.327 0h14.262m-1.876-4.352l-16.843-.263M20.105 18l-.783 5.48M13.575 18l-.78 5.377");
}

.m6n3gsbty {
  cx: 10.225px;
  cy: 27.442px;
  r: 2.558px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.qg3in1ban {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M20.662 18h7.015l7.523 5.591l8.031.765l1.081 1.266l.188 2.321h-9.77m-9.35-4.352h9.82m-.708 2.031h9.82");
}

.w53nakbdl {
  cx: 29.866px;
  cy: 27.442px;
  r: 2.558px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.ybh0g2boo {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M15.423 27.942a2.556 2.556 0 0 0 5.014 0m14.399 0a2.556 2.556 0 0 0 5.014 0");
}

</style>
