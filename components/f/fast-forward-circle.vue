<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ppq86hbfu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:fast-forward-circle" /></template>
<style>
.ppq86hbfu {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m3.98 6.61l6.54 4.53q1.23.86 0 1.72l-6.54 4.53q-1.23.86-1.23-.64v-9.5q0-1.5 1.23-.64m9.5 0l6.54 4.53q1.23.86 0 1.72l-6.54 4.53q-1.23.86-1.23-.64v-9.5q0-1.5 1.23-.64");
}

</style>
