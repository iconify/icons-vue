<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="i9clfwm2k"/><path class="ocqyx9l9y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:bunq" /></template>
<style>
.i9clfwm2k {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M38.5 5.5h-29a4 4 0 0 0-4 4v29a4 4 0 0 0 4 4h29a4 4 0 0 0 4-4v-29a4 4 0 0 0-4-4");
}

.ocqyx9l9y {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M17.488 20.571v4.27a2.59 2.59 0 0 0 2.588 2.588h0a2.59 2.59 0 0 0 2.588-2.588v-4.27m7.927 6.858v-4.27a2.59 2.59 0 0 0-2.588-2.588h0a2.59 2.59 0 0 0-2.588 2.588v4.27M9.5 23.159a2.59 2.59 0 0 1 2.588-2.588h0a2.59 2.59 0 0 1 2.588 2.588v1.682a2.59 2.59 0 0 1-2.588 2.588h0A2.59 2.59 0 0 1 9.5 24.841m0 2.588V17.077m29 7.764a2.59 2.59 0 0 1-2.588 2.588h0a2.59 2.59 0 0 1-2.588-2.588V23.16a2.59 2.59 0 0 1 2.588-2.588h0A2.59 2.59 0 0 1 38.5 23.16m0-2.589v10.352");
}

</style>
