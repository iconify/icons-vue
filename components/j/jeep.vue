<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="i9clfwm2k"/><path class="klca2zbna"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:jeep" /></template>
<style>
.i9clfwm2k {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M38.5 5.5h-29a4 4 0 0 0-4 4v29a4 4 0 0 0 4 4h29a4 4 0 0 0 4-4v-29a4 4 0 0 0-4-4");
}

.klca2zbna {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M15.582 18.576V24.7a2.041 2.041 0 1 1-4.082 0v-.678m10.787 1.653a2.041 2.041 0 0 1-3.814-1.011v-1.327a2.041 2.041 0 1 1 4.082 0V24h-4.083m13.946-2.74v8.164m0-4.796a2.041 2.041 0 0 0 4.082 0V23.3a2.041 2.041 0 1 0-4.082 0m-3.158 2.41a2.041 2.041 0 0 1-3.814-1.011v-1.326a2.041 2.041 0 1 1 4.082 0v.663h-4.083");
}

</style>
