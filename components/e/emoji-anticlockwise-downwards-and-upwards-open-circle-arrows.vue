<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="i_v-wcbyk"/><path class="bzh84tb8m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:emoji-anticlockwise-downwards-and-upwards-open-circle-arrows" /></template>
<style>
.bzh84tb8m {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m18.173 23.999l-6.343 6.33l-6.33-6.33m24.34 0l6.489-6.33l6.171 6.33");
}

.i_v-wcbyk {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M30.94 13.842c-5.62-3.781-13.24-2.292-17.02 3.327a12.26 12.26 0 0 0-2.09 6.83v6.33m5.403 3.827a12.13 12.13 0 0 0 6.847 2.092c6.765 0 12.249-5.484 12.249-12.249v-6.33");
}

</style>
