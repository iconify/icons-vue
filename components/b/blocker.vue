<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<rect transform="rotate(45 18.55 29.454)" class="b96plfbju"/><path class="oin3g0b5x"/><rect transform="rotate(135 10.917 36.307)" class="ok17yl_nw"/><path class="b7h7mab-d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:blocker" /></template>
<style>
.b7h7mab-d {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M34.662 12.828a5.66 5.66 0 0 1 0 8.004L23.66 31.835h0l-8.005-8.005h0l11.003-11.002a5.66 5.66 0 0 1 8.004 0m.008.002l2.86-2.87m-11.77 3.77l2.32 2.32m-7.54 2.9l2.32 2.32m.29-4.93l3.87 3.87m-9.09 1.35l3.87 3.87");
}

.b96plfbju {
  width: 17.02px;
  height: 3.87px;
  x: 10.04px;
  y: 27.52px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  rx: 1.93px;
}

.oin3g0b5x {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m15.989 29.638l1.598 1.598l-4.773 4.773l-1.598-1.598z");
}

.ok17yl_nw {
  width: 3.1px;
  height: 9.81px;
  x: 9.37px;
  y: 31.4px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  rx: 1.55px;
}

</style>
