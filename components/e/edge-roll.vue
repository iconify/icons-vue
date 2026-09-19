<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="i1xkrt_rh"/><rect class="lym-8pzot"/><rect class="t9dblbbyo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:edge-roll" /></template>
<style>
.i1xkrt_rh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m8.219 13.8l15.645 9.374l15.918-9.19L23.864 4.5z");
}

.lym-8pzot {
  width: 8.565px;
  height: 8.565px;
  x: 13.476px;
  y: 30.044px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  rx: 0.664px;
  ry: 0.664px;
}

.t9dblbbyo {
  width: 8.565px;
  height: 8.565px;
  x: 25.941px;
  y: 34.935px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  rx: 0.664px;
  ry: 0.664px;
}

</style>
