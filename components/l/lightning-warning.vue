<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="r96myabst"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:lightning-warning" /></template>
<style>
.r96myabst {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m8.907 5.904l-3.589 4.71A1.486 1.486 0 0 0 6.5 13h1.032a1.75 1.75 0 0 1 1.738 1.954L9 17.25a1.17 1.17 0 0 0 2.093.846l3.589-4.71A1.486 1.486 0 0 0 13.5 11h-1.032a1.75 1.75 0 0 1-1.738-1.954L11 6.75a1.17 1.17 0 0 0-2.093-.846M20 4v10m0 4.25h.01");
}

</style>
