<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="x0f7zyb6j"/><path class="b6oynbb7n"/><path class="txbdehe8i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:bitkub" /></template>
<style>
.b6oynbb7n {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M16.188 35.672L4.517 24l11.671-11.672l8.163 8.163M29.247 24a2.778 2.778 0 1 1 .003.142");
}

.txbdehe8i {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M31.812 12.328L43.483 24l-11.67 11.672l-8.163-8.163");
}

.x0f7zyb6j {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M18.753 24a2.778 2.778 0 1 1-.003-.142");
}

</style>
