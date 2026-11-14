<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="v0de5pb9y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:h2s-alarm" /></template>
<style>
.v0de5pb9y {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M7.5 16v-4.5a4.5 4.5 0 0 1 9 0V16M5 16h14v4H5Zm-.5-6a7.5 7.5 0 0 1 3-5.5m12 5.5a7.5 7.5 0 0 0-3-5.5");
}

</style>
