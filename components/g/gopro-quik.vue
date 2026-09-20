<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="i9clfwm2k"/><path class="wm1vazb8v"/><circle class="s4br-3bqh"/><path class="ht1jihrug"/><rect class="jswq03b0f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:gopro-quik" /></template>
<style>
.ht1jihrug {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M29.471 22.346V30.5m-12.234 0l-4.077-4.028");
}

.i9clfwm2k {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M38.5 5.5h-29a4 4 0 0 0-4 4v29a4 4 0 0 0 4 4h29a4 4 0 0 0 4-4v-29a4 4 0 0 0-4-4");
}

.jswq03b0f {
  width: 8.154px;
  height: 12.308px;
  x: 9.083px;
  y: 18.192px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  rx: 4.077px;
  ry: 4.077px;
}

.s4br-3bqh {
  cx: 29.471px;
  cy: 18.577px;
  r: 0.75px;
  fill: currentColor;
}

.wm1vazb8v {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M20.244 22.346v5.077a3.077 3.077 0 1 0 6.154 0v-5.077m0 5.077V30.5m6.365-12.308V30.5m.001-2.614l5.571-5.544m-3.797 3.779l4.379 4.361");
}

</style>
