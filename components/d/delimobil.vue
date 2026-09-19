<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<rect class="j3s9ivbxi"/><path class="k8mp1v4do"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:delimobil" /></template>
<style>
.j3s9ivbxi {
  width: 37px;
  height: 37px;
  x: 5.5px;
  y: 5.5px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  rx: 4px;
  ry: 4px;
}

.k8mp1v4do {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M5.703 39.77A18.5 18.5 0 0 1 17.74 25.092L5.5 14.75m9.25 27.75a9.25 9.25 0 0 1 18.5 0h0m9.25-27.75H19.829l16.114 13.621a18.5 18.5 0 0 1 6.354 11.391");
}

</style>
