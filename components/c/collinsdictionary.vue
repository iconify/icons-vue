<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="i9clfwm2k"/><path class="iwhfu4bmi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:collinsdictionary" /></template>
<style>
.i9clfwm2k {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M38.5 5.5h-29a4 4 0 0 0-4 4v29a4 4 0 0 0 4 4h29a4 4 0 0 0 4-4v-29a4 4 0 0 0-4-4");
}

.iwhfu4bmi {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M9.5 19.844h3.099v8.265H9.5zm23.525 8.265v-8.265h1.86A3.616 3.616 0 0 1 38.5 23.46v1.033a3.616 3.616 0 0 1-3.616 3.616zm-11.263-2.772v.034a2.738 2.738 0 1 1-5.475 0v-2.79a2.738 2.738 0 1 1 5.475 0v.034m2.788 2.804a2.738 2.738 0 1 0 5.476 0v-2.79a2.738 2.738 0 1 0-5.475 0z");
}

</style>
