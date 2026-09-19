<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="uo47pyvli"/><path class="d5_oyfd9v"/><rect class="e0dpwuyrk"/><path class="yn0vb5bbj"/><rect class="c115_cc2m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:loklok-alt-1" /></template>
<style>
.c115_cc2m {
  width: 4.577px;
  height: 6.908px;
  x: 29.349px;
  y: 20.546px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  rx: 2.288px;
  ry: 2.288px;
}

.d5_oyfd9v {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M8.5 20.546v6.908h3.454m7.517-6.908v6.908m3.713 0L20.34 24l2.844-3.43M20.34 24h-.869");
}

.e0dpwuyrk {
  width: 4.577px;
  height: 6.908px;
  x: 13.033px;
  y: 20.546px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  rx: 2.288px;
  ry: 2.288px;
}

.uo47pyvli {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M9.5 42.5h29a4 4 0 0 0 4-4v-29a4 4 0 0 0-4-4h-29a4 4 0 0 0-4 4v29a4 4 0 0 0 4 4");
}

.yn0vb5bbj {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M24.816 20.546v6.908h3.454m7.517-6.908v6.908m3.713 0L36.656 24l2.844-3.43M36.656 24h-.869");
}

</style>
