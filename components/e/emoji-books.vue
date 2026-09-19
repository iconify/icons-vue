<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="rg3fvdb0g"/><path class="c4-65vb-e"/><path class="d0o0abh2d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:emoji-books" /></template>
<style>
.c4-65vb-e {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M8.109 20.756a3.302 3.302 0 0 0-.342 6.365l17.257 5.038L42.5 27.167");
}

.d0o0abh2d {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M8.109 27.32a3.302 3.302 0 0 0-.342 6.364l17.257 5.038L42.5 33.73M25.024 9.278L42.5 14.233l-17.476 4.992l-16.942-4.974zM42.5 14.233V33.73");
}

.rg3fvdb0g {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M8.109 14.263a3.302 3.302 0 0 0-.342 6.365l17.257 5.038L42.5 20.674");
}

</style>
