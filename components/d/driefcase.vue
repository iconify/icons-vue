<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="swmxm7b6v"/><path class="yzsns7bhf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:driefcase" /></template>
<style>
.swmxm7b6v {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M23.235 42.262V23.061h19.2v-6.315H30.95V5.262H16.919v11.484H5.435v14.031h11.484v11.485z");
}

.yzsns7bhf {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M27.685 42.262v-14.75h14.75m-14.75 0l13.069 13.069");
}

</style>
