<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<rect class="pocelwxsf"/><path class="r40ase1ra"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:googlesheets" /></template>
<style>
.pocelwxsf {
  width: 35.455px;
  height: 28.364px;
  x: 8.046px;
  y: 9.818px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  rx: 4.432px;
  ry: 4.432px;
}

.r40ase1ra {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M8.212 34.953A5.67 5.67 0 0 1 4.5 29.628V18.372a5.67 5.67 0 0 1 3.712-5.325M20.455 29.54h18.613m-4.432 4.21V19.568");
}

</style>
