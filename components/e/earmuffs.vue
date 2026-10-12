<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="y9237njbg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:earmuffs" /></template>
<style>
.y9237njbg {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M6.5 13.5C6.5 7.75 9 4.25 12 4.25s5.5 3.5 5.5 9.25M9 18a1.1 1.1 0 0 1-1.5 1.5a1.1 1.1 0 0 1-2 0A1.1 1.1 0 0 1 4 18a1.1 1.1 0 0 1 0-2a1.1 1.1 0 0 1 1.5-1.5a1.1 1.1 0 0 1 2 0A1.1 1.1 0 0 1 9 16a1.1 1.1 0 0 1 0 2m11 0a1.1 1.1 0 0 1-1.5 1.5a1.1 1.1 0 0 1-2 0A1.1 1.1 0 0 1 15 18a1.1 1.1 0 0 1 0-2a1.1 1.1 0 0 1 1.5-1.5a1.1 1.1 0 0 1 2 0A1.1 1.1 0 0 1 20 16a1.1 1.1 0 0 1 0 2");
}

</style>
