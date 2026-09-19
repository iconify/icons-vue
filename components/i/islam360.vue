<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<rect class="hro3so77w"/><path class="gsouxnbof"/><path class="t1g3zh_ar"/><rect class="j3s9ivbxi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:islam360" /></template>
<style>
.gsouxnbof {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M21.443 24.694c0-.766.62-1.388 1.387-1.388h2.34c.766 0 1.387.621 1.387 1.388v9.419c0 .766-.62 1.387-1.387 1.387h-2.34a1.387 1.387 0 0 1-1.387-1.387V13.887c0-.766.62-1.387 1.387-1.387h2.34c.766 0 1.387.621 1.387 1.387v4.129m-13.438-4.129v4.129m-.001 11.968v4.129m1.388-10.665h2.34c.766 0 1.387.621 1.387 1.388v9.277c0 .766-.62 1.387-1.387 1.387h-2.34a1.387 1.387 0 0 1-1.388-1.387");
}

.hro3so77w {
  width: 5.115px;
  height: 23px;
  x: 29.767px;
  y: 12.5px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  rx: 1.387px;
  ry: 1.387px;
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

.t1g3zh_ar {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M16.846 23.448c.766 0 1.387-.62 1.387-1.387v-8.174c0-.766-.62-1.387-1.387-1.387h-2.34c-.766 0-1.388.621-1.388 1.387");
}

</style>
