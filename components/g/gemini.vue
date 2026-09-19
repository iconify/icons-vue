<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="d08bv1bht"/><path class="gcfzzrbyo"/><path class="hh9bhqbup"/><path class="qx1ioe51p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:gemini" /></template>
<style>
.d08bv1bht {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M30.167 30.167a12.333 12.333 0 1 1-12.333-12.333");
}

.gcfzzrbyo {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M17.833 17.833a12.333 12.333 0 1 1 12.333 12.333");
}

.hh9bhqbup {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M42.5 17.833H17.833v12.334");
}

.qx1ioe51p {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M5.5 30.167h24.667V17.833");
}

</style>
