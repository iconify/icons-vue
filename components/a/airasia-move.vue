<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="cfa11tbgn"/><rect transform="rotate(-45 24 24)" class="a04yairnb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:airasia-move" /></template>
<style>
.a04yairnb {
  width: 45.77px;
  height: 15.892px;
  x: 1.115px;
  y: 16.054px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  rx: 7.946px;
  ry: 7.946px;
}

.cfa11tbgn {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m15.125 38.335l-2.73-8.201l5.471 5.471l-2.727-8.199l5.463 5.463m6.709-17.652l1.343 9.601l-5.472-5.472m13.846-4.986a2.92 2.92 0 0 1-.752 2.836h0a2.92 2.92 0 0 1-4.13 0l-1.342-1.343a2.92 2.92 0 0 1 0-4.13h0a2.92 2.92 0 0 1 4.13 0l.671.672l-2.589 2.589m-13.86 12.518a2.92 2.92 0 0 1 4.13-4.13l1.342 1.342a2.92 2.92 0 0 1-4.13 4.13z");
}

</style>
