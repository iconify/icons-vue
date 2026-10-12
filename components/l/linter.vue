<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="prerp1uph"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:linter" /></template>
<style>
.prerp1uph {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.75 4.75h11.5m-11.5 5h18.5m-18.5 5h13m-13 5c1.25-1.5 2-1.5 3.25 0s2 1.5 3.25 0s2-1.5 3.25 0s2 1.5 3.25 0");
}

</style>
