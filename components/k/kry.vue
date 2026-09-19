<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="i9clfwm2k"/><path class="fm2yrpb6w"/><path class="kp_c18bzy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:kry" /></template>
<style>
.fm2yrpb6w {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M34.5 24.99v4.127a3.057 3.057 0 0 1-3.057 3.056h0a3.05 3.05 0 0 1-2.16-.895");
}

.i9clfwm2k {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M38.5 5.5h-29a4 4 0 0 0-4 4v29a4 4 0 0 0 4 4h29a4 4 0 0 0 4-4v-29a4 4 0 0 0-4-4");
}

.kp_c18bzy {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M34.5 19.947v5.043a3.057 3.057 0 0 1-3.057 3.057h0a3.057 3.057 0 0 1-3.056-3.057v-5.043m-5.915 3.057a3.057 3.057 0 0 1 3.056-3.057h0m-3.056 0v8.1M13.5 15.826v12.227m.001-2.597l5.534-5.507m-3.772 3.754l4.35 4.332");
}

</style>
