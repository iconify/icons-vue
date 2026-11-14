<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wr3d681bi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:cfl-bulb" /></template>
<style>
.wr3d681bi {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M9 14.5v-2h6A2.25 2.25 0 0 0 15 8H9a2.25 2.25 0 0 1 0-4.5h6m-5.25 11h4.5A1.75 1.75 0 0 1 16 16.25A1.75 1.75 0 0 1 14.25 18h-4.5A1.75 1.75 0 0 1 8 16.25a1.75 1.75 0 0 1 1.75-1.75m.75 6.25h3");
}

</style>
