<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="blumuxbam"/><rect transform="matrix(-1 0 0 -1 38.28 46.71)" class="krv11eb1h"/><path class="h5xpp9yee"/><rect class="j3s9ivbxi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:gopuff" /></template>
<style>
.blumuxbam {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M16.671 31.67a3.49 3.49 0 0 0 5.959-2.468v-6.981c0-2.549 1.16-3.823 1.16-3.823");
}

.h5xpp9yee {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M25.37 22.22a3.49 3.49 0 1 1 6.981 0v2.27a3.49 3.49 0 1 1-6.981 0z");
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

.krv11eb1h {
  width: 6.981px;
  height: 9.25px;
  x: 15.649px;
  y: 18.73px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  rx: 3.491px;
  ry: 3.491px;
}

</style>
