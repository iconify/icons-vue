<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<rect class="j3s9ivbxi"/><path class="rns0nelax"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:cbp-mpc" /></template>
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

.rns0nelax {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M10.5 28.57v-9.15l4.58 9.16l4.58-9.146v9.146m2.852 0v-9.16h2.998c1.695 0 3.07 1.377 3.07 3.076s-1.374 3.076-3.07 3.076h-2.999m14.989-.064v.038a3.034 3.034 0 1 1-6.068 0v-3.092a3.034 3.034 0 1 1 6.068 0v.038");
}

</style>
