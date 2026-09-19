<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<rect transform="rotate(-28.888 24 24)" class="nby6dddoa"/><rect transform="rotate(61.112 22.783 24.671)" class="x3dq9jbla"/><path class="q7rpikb9h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:fortitoken-mobile" /></template>
<style>
.nby6dddoa {
  width: 36.283px;
  height: 19.096px;
  x: 5.859px;
  y: 14.452px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  rx: 2.78px;
  ry: 2.78px;
}

.q7rpikb9h {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m38.864 19.438l-3.079-5.58");
}

.x3dq9jbla {
  width: 13.536px;
  height: 27.943px;
  x: 16.015px;
  y: 10.7px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  rx: 0.927px;
  ry: 0.927px;
}

</style>
