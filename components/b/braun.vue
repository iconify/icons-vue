<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<rect class="j3s9ivbxi"/><path class="rvkb8tnaq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:braun" /></template>
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

.rvkb8tnaq {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M11.219 24a2 2 0 1 1 0 4h-3.3v-8h3.3a2 2 0 1 1 0 4m0 0h-3.3m7.007 4v-8h2.62c1.48 0 2.68 1.203 2.68 2.687s-1.2 2.686-2.68 2.686h-2.62m2.619 0l2.619 2.625m5.684-2.648h-3.544M21.426 28l2.65-8l2.65 8m1.2-8v5.35a2.65 2.65 0 1 0 5.3 0V20m1.555 8v-8l5.3 8v-8");
}

</style>
