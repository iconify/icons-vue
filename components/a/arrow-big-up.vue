<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jj_6gqbme"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:arrow-big-up" /></template>
<style>
.jj_6gqbme {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m13.856 5.356l4.553 4.553a.932.932 0 0 1-.659 1.591a2.25 2.25 0 0 0-2.25 2.25v4.125a2.625 2.625 0 0 1-2.625 2.625h-1.75A2.625 2.625 0 0 1 8.5 17.875V13.75a2.25 2.25 0 0 0-2.25-2.25a.932.932 0 0 1-.659-1.591l4.553-4.553a2.625 2.625 0 0 1 3.712 0");
}

</style>
