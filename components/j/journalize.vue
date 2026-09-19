<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="rfhflkzzu"/><path class="s29t4nvee"/><path class="hwayhybhb"/><path class="ahrf1gb1m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:journalize" /></template>
<style>
.ahrf1gb1m {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  d: path("M38.046 35.505h4.351");
}

.hwayhybhb {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m40.237 40.871l-2.19-5.336V8.1a.97.97 0 0 1 .97-.97h2.406a.97.97 0 0 1 .97.97v27.42z");
}

.rfhflkzzu {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M9.682 5.5H7.605a2.01 2.01 0 0 0-2.002 2.003v32.994c0 1.102.9 2.003 2.002 2.003h2.077m0-37v37H33.2a2.01 2.01 0 0 0 2.003-2.002V7.503A2.01 2.01 0 0 0 33.2 5.5z");
}

.s29t4nvee {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  d: path("M30.492 5.5v13.264l-2.998-2.077l-3.017 2.057l-.02-13.244");
}

</style>
