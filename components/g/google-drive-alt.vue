<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="uyachdcbj"/><path class="s9gywebub"/><path class="njn9ae1vm"/><path class="d7-w57a_i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:google-drive-alt" /></template>
<style>
.d7-w57a_i {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m36.95 18.559l-5.53-9.576a3.95 3.95 0 0 0-1.436-1.437L24 17.906l7.03 12.188h11.948c0-.675-.174-1.35-.522-1.959z");
}

.njn9ae1vm {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m24 17.906l5.985-10.36a3.8 3.8 0 0 0-1.959-.522h-8.052c-.697 0-1.372.196-1.96.522zm7.03 12.188H16.97l-5.985 10.36a3.8 3.8 0 0 0 1.959.522h22.112c.697 0 1.371-.196 1.959-.522z");
}

.s9gywebub {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m24 17.906l-5.985-10.36a3.95 3.95 0 0 0-1.436 1.437L5.522 28.135A3.94 3.94 0 0 0 5 30.094h11.97zm13.015 22.548a3.95 3.95 0 0 0 1.436-1.437l.697-1.197l3.33-5.767c.348-.61.522-1.284.522-1.96H31.029l2.547 5.007z");
}

.uyachdcbj {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m7.873 36.123l1.676 2.894c.348.61.849 1.088 1.436 1.437l5.985-10.36H5c0 .675.174 1.35.522 1.959z");
}

</style>
