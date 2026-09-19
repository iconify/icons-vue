<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<rect class="w2888cbgh"/><rect class="pcmo7exrt"/><rect transform="matrix(-1 0 0 -1 69 64)" class="x9b7x-b3m"/><rect transform="matrix(-1 0 0 -1 69 22)" class="o12ya4bqq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:eidetic" /></template>
<style>
.o12ya4bqq {
  width: 16px;
  height: 11px;
  x: 26.5px;
  y: 5.5px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  rx: 4px;
  ry: 4px;
}

.pcmo7exrt {
  width: 16px;
  height: 11px;
  x: 5.5px;
  y: 31.5px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  rx: 4px;
  ry: 4px;
}

.w2888cbgh {
  width: 16px;
  height: 21px;
  x: 5.5px;
  y: 5.5px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  rx: 4px;
  ry: 4px;
}

.x9b7x-b3m {
  width: 16px;
  height: 21px;
  x: 26.5px;
  y: 21.5px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  rx: 4px;
  ry: 4px;
}

</style>
