<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jm12e236j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:bedtime-story" /></template>
<style>
.jm12e236j {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M11.69 2.77a3.25 3.25 0 1 0 3.47 3.97a2.75 2.75 0 0 1-3.47-3.97M12 13c-2-1.25-5-1.75-9.25-1.5v8.25C7 19.5 10 20 12 21.25c2-1.25 5-1.75 9.25-1.5V11.5C17 11.25 14 11.75 12 13m0 0v8.25");
}

</style>
