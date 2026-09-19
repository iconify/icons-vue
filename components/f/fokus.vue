<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="i2-ojrhtu"/><path class="jv592ccpe"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:fokus" /></template>
<style>
.i2-ojrhtu {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m4.5 23.159l12.346 12.413l19.381-19.488l-3.636-3.656l-15.63 15.715l-8.71-8.756Z");
}

.jv592ccpe {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m20.482 31.916l3.637 3.656L43.5 16.084l-3.636-3.656l-3.637 3.656m-15.674 8.359l-5.028-5.056l-3.637 3.656");
}

</style>
