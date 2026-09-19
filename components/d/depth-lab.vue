<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="paryct4qy"/><path class="u4ktx5fci"/><path class="s2d8psb-d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:depth-lab" /></template>
<style>
.paryct4qy {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M40.887 14.25L24 4.5L7.113 14.25v19.5L24 43.5l16.887-9.75z");
}

.s2d8psb-d {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M31.12 11.668v16.443l-14.24 8.221V19.889z");
}

.u4ktx5fci {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M7.113 14.25L24 24l16.887-9.75M24 43.5V24");
}

</style>
