<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="r9to-zn5q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:guest-book" /></template>
<style>
.r9to-zn5q {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M21.5 11.798V4c-4-.5-7.25 0-9.5 1.5C9.75 4 6.5 3.5 2.5 4v13.5c4-.5 7.25 0 9.5 1.5q.297-.198.617-.373M12 5.5V19m3.211.946l.2-1.001a1.5 1.5 0 0 1 .41-.766l3.554-3.554a.884.884 0 0 1 1.25 0a.884.884 0 0 1 0 1.25l-3.787 3.787a1.5 1.5 0 0 1-.189.16l-.774.553a.425.425 0 0 1-.664-.429");
}

</style>
