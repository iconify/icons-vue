<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="f5rwj8lsf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:freetube" /></template>
<style>
.f5rwj8lsf {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M13.5 42.5h3v-35a2 2 0 0 0-2-2h-7a2 2 0 0 0-2 2v27a8 8 0 0 0 8 8m3-35v7a2 2 0 0 0 2 2h16a8 8 0 0 0 8-8v-3h-24a2 2 0 0 0-2 2m13.908 15.492l-12.485-5.828a1 1 0 0 0-1.423.906v11.655a1 1 0 0 0 1.423.906l12.485-5.827a1 1 0 0 0 0-1.813Z");
}

</style>
