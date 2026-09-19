<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="g2wj9jbhp"/><path class="m6mpg7i3o"/><path class="dml1itb0s"/><path class="jlrmzqb7w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:icon-pack-studio-exporter" /></template>
<style>
.dml1itb0s {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m30.612 20.919l3.71-3.709l-3.71-3.71m-7.278 15.318a4.39 4.39 0 0 0 3.663 1.972h7.325M13.678 16.076h2.758a4.39 4.39 0 0 1 4.094 2.81");
}

.g2wj9jbhp {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M9.5 5.5h29c2.216 0 4 1.784 4 4v29c0 2.216-1.784 4-4 4h-29c-2.216 0-4-1.784-4-4v-29c0-2.216 1.784-4 4-4");
}

.jlrmzqb7w {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m30.612 27.081l3.71 3.709l-3.71 3.71");
}

.m6mpg7i3o {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M13.678 31.924h2.758a4.39 4.39 0 0 0 4.252-3.308l2.057-8.1a4.39 4.39 0 0 1 4.252-3.306h7.325");
}

</style>
