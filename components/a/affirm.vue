<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="y97w7_bfl"/><path class="jragd8b7e"/><path class="pbotbjbyj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:affirm" /></template>
<style>
.jragd8b7e {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M21.898 29.356c-2.229 0-4.036 1.82-4.036 4.066s1.807 4.066 4.036 4.066h2.137c3.364 0 6.091-2.748 6.091-6.138");
}

.pbotbjbyj {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M19.397 22.835c1.479-1.482 2.515-1.612 5.37-1.612c3.241 0 5.37 1.426 5.37 5.28v10.985");
}

.y97w7_bfl {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M42.01 37.488a19.4 19.4 0 0 0 1.49-7.476c0-10.77-8.73-19.5-19.5-19.5s-19.5 8.73-19.5 19.5c0 2.65.534 5.173 1.49 7.476m15.908-8.132h8.24");
}

</style>
