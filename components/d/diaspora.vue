<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="tae-9j1jr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:diaspora" /></template>
<style>
.tae-9j1jr {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M19 4.49h10v13.08l12.45-4L44.5 23l-12.45 4l7.67 10.57l-8 5.87L24 32.94l-7.67 10.57l-8-5.87L16 27.07L3.5 23l3.09-9.5l12.45 4Z");
}

</style>
