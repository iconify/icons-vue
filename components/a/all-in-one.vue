<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="x-6j88b3o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:all-in-one" /></template>
<style>
.x-6j88b3o {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M6.875 3h10.25A4.375 4.375 0 0 1 21.5 7.375v4.75a4.375 4.375 0 0 1-4.375 4.375H6.875A4.375 4.375 0 0 1 2.5 12.125v-4.75A4.375 4.375 0 0 1 6.875 3M2.5 13h19m-11 3.5l-1 4m4-4l1 4m-8 0h11");
}

</style>
