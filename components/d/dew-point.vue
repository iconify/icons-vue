<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="pso_zgp2z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:dew-point" /></template>
<style>
.pso_zgp2z {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M5 15.45v-9.6a2 2 0 0 1 4 0v9.6a3.25 3.25 0 1 1-4 0m11.22-8.56l-3.48 6.63a4.25 4.25 0 1 0 7.52 0l-3.48-6.63q-.28-.53-.56 0");
}

</style>
