<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="yq85jj0ta"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:fog-warning" /></template>
<style>
.yq85jj0ta {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M7.71 13.64a3.36 3.36 0 0 1-.46-6.69a4.83 4.83 0 0 1 8.95-1.16a3.78 3.78 0 0 1-.51 7.85ZM4.5 17.25H16M8.5 21h11");
}

</style>
