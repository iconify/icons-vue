<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="i9clfwm2k"/><path class="g5xpvzb4e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:ferns-n-petals" /></template>
<style>
.g5xpvzb4e {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M26.28 28.458v-5.551a3.364 3.364 0 1 0-6.729 0m0 5.551v-8.916m10.077 5.552a3.364 3.364 0 1 0 6.729 0v-2.187a3.364 3.364 0 1 0-6.729 0m0-3.365V33m-15.991-4.542V17.355c0-1.3 1.055-2.355 2.355-2.355c1.16 0 1.883.343 2.38.985m-6.729 3.557h4.71");
}

.i9clfwm2k {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M38.5 5.5h-29a4 4 0 0 0-4 4v29a4 4 0 0 0 4 4h29a4 4 0 0 0 4-4v-29a4 4 0 0 0-4-4");
}

</style>
