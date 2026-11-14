<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jhacxrt0c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:body-female" /></template>
<style>
.jhacxrt0c {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M13.224 19.011c-.162.308-.523.489-.974.489h-1c-.5 0-1-.5-1-1L10 15a.781.781 0 0 0-1.5 0l-.25 3.5c0 .5-.5 1-1 1h-1c-.75 0-1.25-.5-1-1.25L5 14.75l1.75-2.25l-.25-.5l-1.25 1.5c-.25.5-.5.75-1.25.75c-1 0-1.5-.5-1.25-1.5l2-2.5C5 9 6 8.75 7.25 8.75h4c1.25 0 2.25.25 2.5 1.5l1.531 1.914m-1.753 1.763a1.8 1.8 0 0 1-.278-.427L12 12l-.25.5l1.466 1.885M7.25 4.25a2 2 0 1 0 4 0a2 2 0 1 0-4 0m8.25 12.5a2.5 2.5 0 1 0 5 0a2.5 2.5 0 1 0-5 0m2.5 2.5V22m-1.75-1.25h3.5");
}

</style>
