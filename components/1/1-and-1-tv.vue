<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<circle class="zdxlghbla"/><path class="pk1edacin"/><path class="j_k1i0pxo"/><circle class="p-r3jprxs"/><path class="svl1-b12v"/><circle class="eb7k_ebcs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:1-and-1-tv" /></template>
<style>
.eb7k_ebcs {
  cx: 33.862px;
  cy: 33.983px;
  r: 1.306px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.j_k1i0pxo {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M16.582 32.67v2.687h9.8v-2.686m5.666-23.509h7.84a2.607 2.607 0 0 1 2.612 2.613v27.063h-2.387c-.126-1.783-2.697-2.058-2.633 0h-2.43c-.02-1.895-2.566-1.961-2.6 0h-3.013V11.775a2.607 2.607 0 0 1 2.612-2.613");
}

.p-r3jprxs {
  cx: 36.203px;
  cy: 23.193px;
  r: 3.919px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.pk1edacin {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M27.543 13.925H5.5v18.746h22.043");
}

.svl1-b12v {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m38.609 11.7l.04 2.984m-1.507-1.492h2.973");
}

.zdxlghbla {
  cx: 38.629px;
  cy: 33.983px;
  r: 1.306px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>
