<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="k79let5fw"/><rect class="lo0fetbxp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:dockwalls" /></template>
<style>
.k79let5fw {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M38.5 9.5c2.21 0 4 1.79 4 4v25c0 2.21-1.79 4-4 4h-25c-2.21 0-4-1.79-4-4");
}

.lo0fetbxp {
  width: 33px;
  height: 33px;
  x: 5.5px;
  y: 5.5px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  rx: 4px;
  ry: 4px;
}

</style>
