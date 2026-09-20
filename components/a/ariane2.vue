<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="i9clfwm2k"/><path class="ud4ax5n0o"/><circle class="vs0g8db5u"/><path class="n8gd9cxzk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:ariane2" /></template>
<style>
.i9clfwm2k {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M38.5 5.5h-29a4 4 0 0 0-4 4v29a4 4 0 0 0 4 4h29a4 4 0 0 0 4-4v-29a4 4 0 0 0-4-4");
}

.n8gd9cxzk {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M20.537 22.925v5.3m17.5-1.009a2 2 0 0 1-3.738-.99v-1.301a2 2 0 1 1 4 0v.65h-4m-7.919.65a2 2 0 1 1-4 0v-1.3a2 2 0 1 1 4 0m0 3.3v-5.3m5.98 5.3v-3.3a2 2 0 1 0-4 0v3.3m.001-3.3v-2M9.7 28.201l2.599-7.976m2.601 8l-2.601-8m1.731 5.324h-3.465");
}

.ud4ax5n0o {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M16.732 24.925a2 2 0 0 1 2-2m-2 0v5.3");
}

.vs0g8db5u {
  cx: 20.537px;
  cy: 20.475px;
  r: 0.7px;
  fill: currentColor;
}

</style>
