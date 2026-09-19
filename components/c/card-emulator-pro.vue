<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<rect class="e90m4jb0e"/><path class="lq9pkz1do"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:card-emulator-pro" /></template>
<style>
.e90m4jb0e {
  width: 39px;
  height: 29px;
  x: 4.5px;
  y: 9.5px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  rx: 3px;
  ry: 3px;
}

.lq9pkz1do {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M4.5 16.5h39m-10 18v-2m3 2v-2m3 2v-2");
}

</style>
