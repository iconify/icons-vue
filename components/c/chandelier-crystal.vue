<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="i3669xb4r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:chandelier-crystal" /></template>
<style>
.i3669xb4r {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M9.5 3h5M12 3v4.5M4.5 13h15M9 7.5h6L12 13ZM4.5 13s-1.75 3-1.75 4.5a1.75 1.75 0 0 0 3.5 0C6.25 16 4.5 13 4.5 13m7.5 0s-1.75 3-1.75 4.5a1.75 1.75 0 0 0 3.5 0C13.75 16 12 13 12 13m7.5 0s-1.75 3-1.75 4.5a1.75 1.75 0 0 0 3.5 0c0-1.5-1.75-4.5-1.75-4.5");
}

</style>
