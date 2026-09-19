<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="cs03lyz4k"/><circle class="xz15mjbca"/><circle class="uayj8bcjb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:looper" /></template>
<style>
.cs03lyz4k {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M4.069 17.402A20.995 20.995 0 0 1 24.001 3.005c11.595 0 20.994 9.4 20.994 20.995c0 1.426-.145 2.848-.433 4.245m-.619 2.32A20.995 20.995 0 0 1 24 44.995c-11.595 0-20.995-9.4-20.995-20.995c0-1.439.148-2.874.442-4.283");
}

.uayj8bcjb {
  cx: 44.279px;
  cy: 29.434px;
  r: 1.221px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.xz15mjbca {
  cx: 3.721px;
  cy: 18.566px;
  r: 1.221px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>
