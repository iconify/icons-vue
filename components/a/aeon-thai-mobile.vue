<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="hz-m3pjgi"/><path class="i2qtxgp2z"/><path class="ai54ch02g"/><rect class="j3s9ivbxi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:aeon-thai-mobile" /></template>
<style>
.ai54ch02g {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M20.684 27.669h-4.347v-7.338m15.983 7.318v-7.298l6.18 7.298v-7.298");
}

.hz-m3pjgi {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M26.463 23.994c-.003.622-2.947 1.125-6.577 1.125s-6.575-.504-6.575-1.126c.003-.622 2.946-1.126 6.575-1.126c3.632 0 6.576.504 6.577 1.127");
}

.i2qtxgp2z {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m9.5 27.669l5.642-7.338h5.542M30.451 24c0 2.214-2.092 4.008-4.673 4.008S21.103 26.214 21.103 24s2.092-4.008 4.673-4.008s4.674 1.794 4.674 4.007z");
}

.j3s9ivbxi {
  width: 37px;
  height: 37px;
  x: 5.5px;
  y: 5.5px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  rx: 4px;
  ry: 4px;
}

</style>
