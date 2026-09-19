<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<rect class="ldxkgm3pb"/><rect class="g-4p1huvo"/><path class="bt6oskb7i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:jal-card" /></template>
<style>
.bt6oskb7i {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m4.5 31.38l39-9.798M38.114 11.5l-8.94 25m4.937-25l-26.439 25M4.5 19.575h5m7 0h27");
}

.g-4p1huvo {
  width: 39px;
  height: 25px;
  x: 4.5px;
  y: 11.5px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  rx: 3px;
  ry: 3px;
}

.ldxkgm3pb {
  width: 7px;
  height: 7px;
  x: 9.5px;
  y: 17px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  rx: 1.5px;
  ry: 1.5px;
}

</style>
