<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="apjplfblw"/><path class="m2j3tacfd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:acura" /></template>
<style>
.apjplfblw {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M22.546 22.48h2.909s6.179 9.455 8.73 18.974c-.707-15.537-.8-18.703-8.73-36.433v15.405h-2.91V5.02c-7.93 17.73-8.023 20.896-8.729 36.433c2.55-9.519 8.73-18.974 8.73-18.974");
}

.m2j3tacfd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M24 5c12.838 0 19 4.622 19 19s-6.162 19-19 19S5 38.378 5 24S11.162 5 24 5");
}

</style>
