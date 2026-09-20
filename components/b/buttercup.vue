<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="rwh5x4b0q"/><path class="fb4-1m_jg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:buttercup" /></template>
<style>
.fb4-1m_jg {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M17.038 32.492a3.16 3.16 0 1 1 2.162 0m-2.162 0l-.008 3.394m2.17-3.394v3.394m0 0a1.085 1.085 0 0 1-2.17 0");
}

.rwh5x4b0q {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M6.616 16.09a11.59 11.59 0 1 1 23.179 0m0 4.23H6.615V43.5h23.18m0-23.18a11.59 11.59 0 0 1 11.59 11.59a11.59 11.59 0 0 1-11.59 11.59M6.616 20.32v-4.23m23.179 4.23v-4.23");
}

</style>
