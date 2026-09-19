<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="y-4p36bav"/><path class="nh9xtyiul"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:letterboxd" /></template>
<style>
.nh9xtyiul {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M30.45 20a7.59 7.59 0 0 0-12.9 0a7.64 7.64 0 0 1 0 8a7.59 7.59 0 0 0 12.9 0a7.64 7.64 0 0 1 0-8m6.46-3.59A7.6 7.6 0 0 0 30.45 20a7.59 7.59 0 0 1 0 8a7.59 7.59 0 1 0 6.46-11.59");
}

.y-4p36bav {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M17.55 20a7.59 7.59 0 1 0 0 8a7.59 7.59 0 0 1 0-8");
}

</style>
