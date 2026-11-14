<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="kksx_brhj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:concrete-finisher" /></template>
<style>
.kksx_brhj {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M5 7.5h11m-9.5 0a4 4 0 0 1 8 0m-7.25 0v1.25a3.25 3.25 0 0 0 6.5 0V7.5m-1.539 13H4c0-3 3-5.5 6.5-5.5a7.2 7.2 0 0 1 3.953 1.17M16.5 18.5h4A1.5 1.5 0 0 1 22 20a1.5 1.5 0 0 1-1.5 1.5h-4A1.5 1.5 0 0 1 15 20a1.5 1.5 0 0 1 1.5-1.5m2.5 0v-3h2.5");
}

</style>
