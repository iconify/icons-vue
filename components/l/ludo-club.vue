<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="o4nzl2bjr"/><rect transform="rotate(-5.471 35.736 24.108)" class="qien8rb9d"/><rect class="j3s9ivbxi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:ludo-club" /></template>
<style>
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

.o4nzl2bjr {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m9.5 20.82l2.164 7.658l3.828-1.082m1.837-8.1l-.16 5.32a2.636 2.636 0 0 0 5.27.158l.159-5.32m2.409 9.06l.768-7.92l1.782.173a3.48 3.48 0 0 1 3.13 3.801l-.097.99a3.48 3.48 0 0 1-3.8 3.13z");
}

.qien8rb9d {
  width: 5.272px;
  height: 7.957px;
  x: 33.1px;
  y: 20.13px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  rx: 2.636px;
  ry: 2.636px;
}

</style>
