<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="juo_eu4qi"/><path class="dca-w8jlb"/><path class="fadkjihkr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:crossword-hebrew" /></template>
<style>
.dca-w8jlb {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M11.189 16.084h.628a2.37 2.37 0 0 0 2.32-1.886l.792-3.801m21.698 8.766v-6.457a2.37 2.37 0 0 0-2.37-2.37h-2.259c-.466 0-1.325.041-1.888.306");
}

.fadkjihkr {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M31.414 10.358v7.265c0 .85-.69 1.54-1.54 1.54m6.22 18.5v-6.457a2.37 2.37 0 0 0-2.37-2.37h-1.43c-.465 0-1.324.041-1.887.306v8.522M14.75 38.937V32.48l-2.37-4.917m2.37 4.917a2.37 2.37 0 0 0 2.37-2.37v-2.547");
}

.juo_eu4qi {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M24 5.5v37M42.5 24h-37m4.925-13.603l1.185 8.827h2.134a4.74 4.74 0 0 0 4.697-4.109l.633-4.718");
}

</style>
