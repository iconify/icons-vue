<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="i9clfwm2k"/><path class="mmltxgblt"/><path class="d6jntfrzx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:coolblue" /></template>
<style>
.d6jntfrzx {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M33.812 5.529a17 17 0 1 1-28.3 18.673");
}

.i9clfwm2k {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M38.5 5.5h-29a4 4 0 0 0-4 4v29a4 4 0 0 0 4 4h29a4 4 0 0 0 4-4v-29a4 4 0 0 0-4-4");
}

.mmltxgblt {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M28.292 24.01a2 2 0 0 1-3.738-.99v-1.3a2 2 0 1 1 4 0v.65h-4m-5.5-2.65v3.3a2 2 0 1 0 4 0v-3.3m0 3.299v2m-11.8-3.299a2 2 0 1 1 4 0v1.3a2 2 0 1 1-4 0m0 1.999v-8m5.5.001v7a1 1 0 0 0 1 1h.3m9.5-17.728v7a1 1 0 0 0 1 1h.3M24 9.992za2 2 0 0 1 2 2v1.3a2 2 0 1 1-4 0v-1.3a2 2 0 0 1 2-2m-5.554 0za2 2 0 0 1 2 2v1.3a2 2 0 1 1-4 0v-1.3a2 2 0 0 1 2-2m-3.455 4.292a2 2 0 0 1-3.737-.993v-1.3a2 2 0 0 1 3.735-.996");
}

</style>
