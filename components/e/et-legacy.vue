<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="km0lalavn"/><path class="h4nudp8xv"/><path class="irw2y12kb"/><path class="nh0hqcche"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:et-legacy" /></template>
<style>
.h4nudp8xv {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M30.209 30.724s2.198 4.482-4.481 4.482H16.25v-4.64h6.231s1.983-1.93 4.492-4.384m3.034-2.976c1.215-1.195 2.463-2.425 3.65-3.602m2.207-2.199a47 47 0 0 0 4.235-4.463l-23.849.008v-1.094a3.683 3.683 0 0 1 4.02-4.021");
}

.irw2y12kb {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M20.269 7.818S21.477 5.363 7.89 4.5v39");
}

.km0lalavn {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M7.89 43.5h26.56s-.745-12.366-4.242-12.777");
}

.nh0hqcche {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M33.71 19.55H16.25v-2.138h19.606m-8.882 8.768H16.25v-2.957h13.738");
}

</style>
