<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="r6-4_laho"/><circle class="cegrky88m"/><circle class="xfvwpnbte"/><path class="j3yboqyfb"/><rect class="zh87zmb4a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:aliexpress" /></template>
<style>
.cegrky88m {
  cx: 13.126px;
  cy: 22.109px;
  r: 1.94px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.j3yboqyfb {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M13.296 23.999c1.072 5.907 6.73 9.825 12.637 8.752A10.87 10.87 0 0 0 34.685 24");
}

.r6-4_laho {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M39.716 8.269a2.77 2.77 0 0 0-2.72-2.77h-26a2.77 2.77 0 0 0-2.73 2.77h0");
}

.xfvwpnbte {
  cx: 34.855px;
  cy: 22.109px;
  r: 1.94px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.zh87zmb4a {
  width: 37px;
  height: 34.206px;
  x: 5.5px;
  y: 8.294px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  rx: 4px;
  ry: 4px;
}

</style>
