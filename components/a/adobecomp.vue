<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="z5vviebyu"/><path class="p4shnwbms"/><path class="dqj8b8b5n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:adobecomp" /></template>
<style>
.dqj8b8b5n {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M28.75 21.12L33.5 24L24 29.75L14.5 24l4.75-2.88m-4.75 8.63l4.75-2.87m-2.37 4.32l4.74-2.9m11.88 1.45L24 35.5M21.62 34l9.5-5.7m-11.87 4.32L24 29.75");
}

.p4shnwbms {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m24 12.5l9.5 5.75L24 24l-9.5-5.75Z");
}

.z5vviebyu {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M40 5.5H7a2 2 0 0 0-2 2v33a2 2 0 0 0 2 2h33a2 2 0 0 0 2-2v-33a2 2 0 0 0-2-2ZM24 24V12.5m9.5 5.75h-19");
}

</style>
