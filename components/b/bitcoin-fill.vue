<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="x_nu60t3v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:bitcoin-fill" /></template>
<style>
.x_nu60t3v {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M5 19L5 5L15.5 5C17.433 5 19 6.567 19 8.5C19 10.433 17.433 12 15.5 12L5 12M5 12L15.5 12C17.433 12 19 13.567 19 15.5C19 17.433 17.433 19 15.5 19L5 19M10 2L10 5M15.5 2L15.5 5M10 19L10 22M15.5 19L15.5 22");
}

</style>
