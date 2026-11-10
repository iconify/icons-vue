<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="f9z849b3j"/><circle class="i9sh72_jp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:lower-brightness" /></template>
<style>
.f9z849b3j {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m24 3.5l6.31 6.31h7.88v7.88L44.5 24l-6.31 6.31v7.88h-7.88L24 44.5l-6.31-6.31H9.81v-7.88L3.5 24l6.31-6.31V9.81h7.88z");
}

.i9sh72_jp {
  cx: 24px;
  cy: 24px;
  r: 8.563px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>
