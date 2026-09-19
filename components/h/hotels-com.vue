<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="x11p8ixmf"/><rect class="i-elhzbgc"/><rect class="ghdd38b_m"/><rect class="yw4hr7r4c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:hotels-com" /></template>
<style>
.ghdd38b_m {
  width: 8px;
  height: 8px;
  x: 20.5px;
  y: 19.5px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  rx: 1px;
  ry: 1px;
}

.i-elhzbgc {
  width: 8px;
  height: 8px;
  x: 7.5px;
  y: 19.5px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  rx: 1px;
  ry: 1px;
}

.x11p8ixmf {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M38.5 5.5H14.328a2 2 0 0 0-1.414.586L5.5 13.5h29v29l7.414-7.414a2 2 0 0 0 .586-1.414V9.5a4 4 0 0 0-4-4");
}

.yw4hr7r4c {
  width: 8px;
  height: 8px;
  x: 20.5px;
  y: 32.5px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  rx: 1px;
  ry: 1px;
}

</style>
