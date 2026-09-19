<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<rect class="j3s9ivbxi"/><path class="nhqo8eteu"/><circle class="u9k_0vijm"/><path class="o4v6xqbsf"/><circle class="j5ahyib_q"/><path class="ij7fnubfu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:light-meter" /></template>
<style>
.ij7fnubfu {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M25.528 17.93h6.525v12.269h-6.525");
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

.j5ahyib_q {
  cx: 24px;
  cy: 24px;
  r: 1.5px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.nhqo8eteu {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M22.55 30.197h-6.514V17.933h6.514");
}

.o4v6xqbsf {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M20.307 22.748a3.9 3.9 0 0 1 7.388.003m-.002 2.501a3.9 3.9 0 0 1-7.387 0");
}

.u9k_0vijm {
  cx: 13.149px;
  cy: 13.099px;
  r: 1.375px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>
