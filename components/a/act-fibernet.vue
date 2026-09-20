<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="i9clfwm2k"/><path class="ro2dm_b3e"/><circle class="y01gup4oe"/><path class="oh1gknb4d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:act-fibernet" /></template>
<style>
.i9clfwm2k {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M38.5 5.5h-29a4 4 0 0 0-4 4v29a4 4 0 0 0 4 4h29a4 4 0 0 0 4-4v-29a4 4 0 0 0-4-4");
}

.oh1gknb4d {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M13.327 28.971v5.193m1.408-3.234c0-1.077.882-1.959 1.96-1.959s1.96.882 1.96 1.96v1.274c0 1.077-.882 1.96-1.96 1.96a1.966 1.966 0 0 1-1.96-1.96m0 1.959v-7.839m8.701 6.859c-.294.588-.98.98-1.666.98a1.966 1.966 0 0 1-1.96-1.96v-1.273c0-1.078.883-1.96 1.96-1.96c1.078 0 1.96.882 1.96 1.96v.686h-3.92m5.197-.687c0-1.077.882-1.959 1.96-1.959m-1.96 0v5.193m6.969 0v-3.233c0-1.078-.882-1.96-1.96-1.96s-1.96.882-1.96 1.96v3.233m0-3.233v-1.96m8.857 4.213c-.294.588-.98.98-1.666.98a1.966 1.966 0 0 1-1.96-1.96v-1.273c0-1.078.882-1.96 1.96-1.96s1.96.882 1.96 1.96v.686h-3.92m5.733-4.312v6.859m-1.078-5.193H40");
}

.ro2dm_b3e {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m19.098 23.744l-3.727-11.469L11.5 23.744m1.29-3.871h5.018m10.248 0zc0 2.15-1.72 3.87-3.87 3.87s-3.87-1.72-3.87-3.87v-3.87c0-2.15 1.72-3.87 3.87-3.87s3.727 1.72 3.727 3.87m.989-3.728H36.5m-3.727 11.469V12.275M8 26.325h3.919M8 30.245h2.548M8 26.325v7.839");
}

.y01gup4oe {
  cx: 13.327px;
  cy: 26.619px;
  r: 0.774px;
  fill: currentColor;
}

</style>
