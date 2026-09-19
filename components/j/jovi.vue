<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<circle class="cpk0fnbgt"/><path class="h-8ctp4dm"/><circle class="c4-qaub9s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:jovi" /></template>
<style>
.c4-qaub9s {
  cx: 23.763px;
  cy: 13.251px;
  r: 4.159px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.cpk0fnbgt {
  cx: 24px;
  cy: 24px;
  r: 21.5px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.h-8ctp4dm {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m15.021 18.149l3.431 3.806h8.029M15.587 38.68l5.882-10.127h3.427l6.631 7.263m-2.554-18.067h5.439v9.135h-5.439");
}

</style>
