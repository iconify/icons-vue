<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="uo47pyvli"/><path class="dup499bpi"/><rect transform="matrix(-1 0 0 -1 23.435 48)" class="f2k0xn97z"/><rect class="rtu0cwbdj"/><path class="ppxi2-bgm"/><circle class="r5mk1rbyf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:gov-br" /></template>
<style>
.dup499bpi {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m26.664 21.062l-2.218 5.876l-2.217-5.876m-8.294 0v6.652a2.217 2.217 0 0 1-2.218 2.217a2.2 2.2 0 0 1-1.568-.65");
}

.f2k0xn97z {
  width: 4.435px;
  height: 5.876px;
  x: 9.5px;
  y: 21.062px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  rx: 2.217px;
  ry: 2.217px;
}

.ppxi2-bgm {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M36.283 23.28c0-1.225.992-2.218 2.217-2.218m-2.217 0v5.876m-6.58-3.658a2.217 2.217 0 1 1 4.435 0v1.44a2.217 2.217 0 1 1-4.435 0m0 2.218v-8.869");
}

.r5mk1rbyf {
  cx: 27.265px;
  cy: 26.724px;
  r: 0.75px;
  fill: currentColor;
}

.rtu0cwbdj {
  width: 4.435px;
  height: 5.876px;
  x: 16.085px;
  y: 21.062px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  rx: 2.217px;
  ry: 2.217px;
}

.uo47pyvli {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M9.5 42.5h29a4 4 0 0 0 4-4v-29a4 4 0 0 0-4-4h-29a4 4 0 0 0-4 4v29a4 4 0 0 0 4 4");
}

</style>
