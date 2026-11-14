<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="dgetznx1a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:drought-well-dry" /></template>
<style>
.dgetznx1a {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m3 7l9-4.5L21 7M6 5.5V14m12-8.5V14M5.625 14h12.75A2.625 2.625 0 0 1 21 16.625v1.25a2.625 2.625 0 0 1-2.625 2.625H5.625A2.625 2.625 0 0 1 3 17.875v-1.25A2.625 2.625 0 0 1 5.625 14M12 2.5v6m-.602 0h1.204a1.166 1.166 0 0 1 1.148 1.375l-.026.143a1.5 1.5 0 0 1-1.476 1.232h-.496a1.5 1.5 0 0 1-1.476-1.232l-.026-.143A1.166 1.166 0 0 1 11.398 8.5");
}

</style>
