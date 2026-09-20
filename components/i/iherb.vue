<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="c801gcb5p"/><circle class="cqwsr0b0d"/><path class="nfbz8vb0i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:iherb" /></template>
<style>
.c801gcb5p {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M38.5 5.5h-29a4 4 0 0 0-4 4v29a4 4 0 0 0 4 4h29a4 4 0 0 0 4-4v-29a4 4 0 0 0-4-4M13.046 19.572v9.384m6.217-9.384v9.384m-6.217-4.71h6.217");
}

.cqwsr0b0d {
  cx: 10.321px;
  cy: 19.865px;
  r: 0.75px;
  fill: currentColor;
}

.nfbz8vb0i {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M10.321 22.739v6.217m18.67-3.889a2.346 2.346 0 0 1 2.346-2.346m-2.346 0v6.217m-2.751-1.184a2.346 2.346 0 0 1-4.384-1.162v-1.525a2.346 2.346 0 0 1 4.692 0v.763h-4.693m11.953-.763a2.346 2.346 0 0 1 4.692 0v1.525a2.346 2.346 0 0 1-4.692 0m0 2.346v-9.383");
}

</style>
