<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jeu6i3b3w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:acorn" /></template>
<style>
.jeu6i3b3w {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M6.5 11h11v.75c0 4.5-2.5 8.25-5.5 9.5c-3-1.25-5.5-5-5.5-9.5ZM5 11c0-3 3-5 7-5s7 2 7 5Zm7-5c0-1.25.5-2.5 1.75-3.25");
}

</style>
