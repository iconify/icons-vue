<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="p13c5lb7i"/><rect class="rtv35sbrf"/><path class="p7uw3-3cg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:ampli" /></template>
<style>
.p13c5lb7i {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  d: path("M24 2.5A21.5 21.5 0 1 1 2.5 24A21.503 21.503 0 0 1 24 2.5Z");
}

.p7uw3-3cg {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M31.974 34.5v-21");
}

.rtv35sbrf {
  width: 17.949px;
  height: 21px;
  x: 14.025px;
  y: 13.5px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  rx: 8.975px;
}

</style>
