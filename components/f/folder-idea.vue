<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="h0qgeuwow"/><path class="e9iy11ecc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:folder-idea" /></template>
<style>
.e9iy11ecc {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M29.179 23.679a5.187 5.187 0 0 0-6.411-5.037c-1.851.427-3.358 1.92-3.796 3.769c-.53 2.234.387 4.305 2.003 5.47c.39.28.597.75.597 1.23v2.646h4.856v-2.745c0-.422.18-.84.526-1.08a5.17 5.17 0 0 0 2.225-4.253M21.572 34.5h4.856");
}

.h0qgeuwow {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M4.5 11.5a3 3 0 0 1 3-3h8.718a4 4 0 0 1 2.325.745l4.914 3.51a4 4 0 0 0 2.325.745H40.5a3 3 0 0 1 3 3v20a3 3 0 0 1-3 3h-33a3 3 0 0 1-3-3z");
}

</style>
