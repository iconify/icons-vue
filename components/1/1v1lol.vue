<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<rect class="j3s9ivbxi"/><path class="mznxi9bcl"/><circle class="h-75lfbme"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:1v1lol" /></template>
<style>
.h-75lfbme {
  cx: 26.445px;
  cy: 29.233px;
  r: 0.75px;
  fill: currentColor;
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

.mznxi9bcl {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M28.67 25.439v4.043h2.14m5.903-4.043v4.043h2.14M9.146 20.01l2.724-1.493v10.965m9.51-9.472l2.724-1.493v10.965m-5.506-5.36l-1.973 5.36l-1.974-5.36m18.942 1.317c.785 0 1.418.597 1.418 1.34v1.364c0 .742-.633 1.34-1.418 1.34s-1.419-.598-1.419-1.34v-1.365c0-.742.633-1.339 1.418-1.339");
}

</style>
