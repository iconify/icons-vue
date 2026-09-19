<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<circle class="gkybav68j"/><path class="akw8d0bcw"/><rect class="z90tl7brf"/><rect class="op__zqaut"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:lineage-recorder" /></template>
<style>
.akw8d0bcw {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M18.679 24h2.538");
}

.gkybav68j {
  cx: 34.554px;
  cy: 24px;
  r: 8.945px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.op__zqaut {
  width: 3.31px;
  height: 17.84px;
  x: 4.5px;
  y: 15.08px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  rx: 1.655px;
}

.z90tl7brf {
  width: 3.31px;
  height: 9.606px;
  x: 11.396px;
  y: 19.197px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  rx: 1.655px;
}

</style>
