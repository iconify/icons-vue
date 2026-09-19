<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<rect class="cpr0-1bcb"/><path class="dmmtrmc_x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:exit-the-gungeon" /></template>
<style>
.cpr0-1bcb {
  width: 37px;
  height: 37px;
  x: 5.5px;
  y: 5.5px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  rx: 6px;
  ry: 6px;
}

.dmmtrmc_x {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m10.625 36.5l5-5m-5 0l5 5m16.75 0l5-5m-5 0l5 5M24.96 37.625c-.689-.9-1.332-1.324-2.565-1.324s-1.766.39-1.766 1.324s.28 1.775 1.5 1.775c1.247 0 1.331-1.775 1.331-1.775h5.496C28.956 35.623 26.736 34 24 34s-4.956 1.623-4.956 3.625h1.584");
}

</style>
