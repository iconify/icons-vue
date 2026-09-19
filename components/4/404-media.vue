<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="qff_jdk9p"/><rect class="j3s9ivbxi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:404-media" /></template>
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

.qff_jdk9p {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m16.767 28.067l1.729-8.134l-5.527 5.464h5.389m13.668 2.67l1.728-8.134l-5.526 5.464h5.388m-10.851 2.67c-1.488 0-2.438-1.206-2.121-2.694l.583-2.746c.316-1.488 1.78-2.694 3.267-2.694h0c1.488 0 2.438 1.206 2.122 2.694l-.584 2.746c-.316 1.488-1.779 2.694-3.267 2.694M10.5 26.031l27-3.458");
}

</style>
