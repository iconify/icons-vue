<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="o0muj2bjf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:control-yoke" /></template>
<style>
.o0muj2bjf {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M4.75 3zA1.75 1.75 0 0 1 6.5 4.75v5a1.75 1.75 0 0 1-1.75 1.75A1.75 1.75 0 0 1 3 9.75v-5A1.75 1.75 0 0 1 4.75 3m14.5 0zA1.75 1.75 0 0 1 21 4.75v5a1.75 1.75 0 0 1-1.75 1.75a1.75 1.75 0 0 1-1.75-1.75v-5A1.75 1.75 0 0 1 19.25 3m-14.5 8.5a3 3 0 0 0 3 3h8.5a3 3 0 0 0 3-3m-7.25 3v7");
}

</style>
