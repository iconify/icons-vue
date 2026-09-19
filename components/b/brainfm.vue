<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="xt-2z-82b"/><circle class="q6uipneug"/><path class="yu2zp6bkd"/><path class="fdclnzmqh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:brainfm" /></template>
<style>
.fdclnzmqh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M8.11 19.964C11.19 11.34 17.3 8.034 24 8.034s12.812 3.306 15.89 11.929");
}

.q6uipneug {
  cx: 24px;
  cy: 27.767px;
  r: 12.198px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.xt-2z-82b {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M31.337 30.683c-.155.909-1.157 6.125-7.272 6.125c-5.967 0-7.391-5.677-7.391-6.125c0 0-.312-1.194 1.12-.953c1.743.293 4.353.371 6.041.371c2.022 0 4.885-.148 6.134-.276c1.38-.139 1.436.461 1.368.858");
}

.yu2zp6bkd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M21.071 25.803a1.877 1.877 0 1 1-3.753 0a1.877 1.877 0 0 1 3.753 0m5.858 0a1.877 1.877 0 1 0 3.753 0a1.877 1.877 0 0 0-3.753 0m12.148-5.839h1.404a3.02 3.02 0 0 1 3.019 3.018v5.242a3.02 3.02 0 0 1-3.019 3.018h-1.404a1.615 1.615 0 0 1-1.614-1.614v-8.05c0-.891.723-1.614 1.614-1.614M8.923 31.243H7.518a3.02 3.02 0 0 1-3.018-3.02v-5.24a3.02 3.02 0 0 1 3.018-3.02h1.405c.89 0 1.614.724 1.614 1.615v8.05c0 .891-.723 1.615-1.614 1.615");
}

</style>
