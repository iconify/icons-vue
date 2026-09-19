<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="d7ehsjb3r"/><path class="n7oow16sq"/><path class="dr05ggfcw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:f-b" /></template>
<style>
.d7ehsjb3r {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M10.095 15.837h5.071v16.326h-5.071zm-3.141 2.077h3.141v12.171H6.954z");
}

.dr05ggfcw {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M41.046 30.086h-3.141V17.915h3.141zM43.5 26.65h-2.454v-5.3H43.5zm-28.334-5.137h17.668v4.973H15.166z");
}

.n7oow16sq {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M4.5 21.35h2.454v5.3H4.5zm33.406 10.813h-5.071V15.837h5.071z");
}

</style>
