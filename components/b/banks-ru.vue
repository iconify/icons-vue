<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<rect class="e1gs15blm"/><rect class="a8gycbctz"/><rect class="mtrc__noh"/><rect class="r3e22eb8e"/><rect class="cumubrhsg"/><rect class="efg9bub5e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:banks-ru" /></template>
<style>
.a8gycbctz {
  width: 11px;
  height: 11px;
  x: 31.5px;
  y: 31.5px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  rx: 4px;
  ry: 4px;
}

.cumubrhsg {
  width: 11px;
  height: 11px;
  x: 18.5px;
  y: 18.5px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  rx: 4px;
  ry: 4px;
}

.e1gs15blm {
  width: 11px;
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

.efg9bub5e {
  width: 11px;
  height: 11px;
  x: 31.5px;
  y: 5.5px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  rx: 4px;
  ry: 4px;
}

.mtrc__noh {
  width: 11px;
  height: 11px;
  x: 18.5px;
  y: 31.5px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  rx: 4px;
  ry: 4px;
}

.r3e22eb8e {
  width: 11px;
  height: 11px;
  x: 31.5px;
  y: 18.5px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  rx: 4px;
  ry: 4px;
}

</style>
