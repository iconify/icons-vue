<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<rect class="j3s9ivbxi"/><path class="wl0-m3lda"/><rect class="n4sk8ebvk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:force-stop" /></template>
<style>
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

.n4sk8ebvk {
  width: 5.308px;
  height: 8.012px;
  x: 24.586px;
  y: 19.994px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  rx: 2.654px;
  ry: 2.654px;
}

.wl0-m3lda {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M32.192 28.006v-8.012h2.623c1.483 0 2.685 1.205 2.685 2.69s-1.202 2.692-2.685 2.692h-2.623m-14.424-5.382h5.308m-2.654 8.012v-8.012m-9.763 7.134c.491.64 1.107.878 1.964.878h1.186a2 2 0 0 0 1.999-1.999V26a2 2 0 0 0-1.999-2h-1.308a2 2 0 0 1-2.001-2c0-1.108.898-2.006 2.005-2.006h1.18c.857 0 1.473.238 1.964.878");
}

</style>
