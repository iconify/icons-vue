<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<rect class="yjjal1b3c"/><circle class="iha5nkb9x"/><circle class="x1kdvxbay"/><path class="e0f8fib2c"/><circle class="xv7s6gbrb"/><circle class="k8lmbkb3p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:droidzebra" /></template>
<style>
.e0f8fib2c {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M5.5 24h37M24 5.5v37");
}

.iha5nkb9x {
  cx: 15px;
  cy: 15px;
  r: 6.5px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.k8lmbkb3p {
  cx: 33.103px;
  cy: 32.988px;
  r: 6.5px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.x1kdvxbay {
  cx: 15.051px;
  cy: 32.988px;
  r: 6.5px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.xv7s6gbrb {
  cx: 33.051px;
  cy: 15px;
  r: 6.5px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.yjjal1b3c {
  width: 37px;
  height: 37px;
  x: 5.5px;
  y: 5.5px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  rx: 10px;
}

</style>
