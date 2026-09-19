<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="z4d5zpbyy"/><path class="fdqsadc9a"/><path class="hze9fs1mj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:fiftheditioncharactersheet" /></template>
<style>
.fdqsadc9a {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M24 13.17L13.74 30.93h20.52z");
}

.hze9fs1mj {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m34.26 30.93l6.63-16.68L24 13.17zM24 13.17L7.11 14.25l6.63 16.68zM13.74 30.93L24 43.5L7.11 33.75zm20.52 0L24 43.5l16.89-9.75zM24 4.5v8.67");
}

.z4d5zpbyy {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m24 4.5l16.89 9.75v19.5L24 43.5L7.11 33.75v-19.5z");
}

</style>
