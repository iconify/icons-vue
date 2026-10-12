<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="i13nk19oj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:darkroom-light" /></template>
<style>
.i13nk19oj {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M12 2.75V7M9.75 7h4.5q1.25 0 1.87 1.09l3.01 5.32q.62 1.09-.63 1.09h-13q-1.25 0-.63-1.09l3.01-5.32Q8.5 7 9.75 7M9 14.5a3 3 0 0 0 6 0Zm3 5v1.75m-3.36-3.39l-1.41 1.41m8.13-1.41l1.41 1.41");
}

</style>
