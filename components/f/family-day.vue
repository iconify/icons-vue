<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="widbvxbgm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:family-day" /></template>
<style>
.widbvxbgm {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M5.5 5a2.5 2.5 0 1 0 5 0a2.5 2.5 0 1 0-5 0Zm-1 16.5v-7.75a3.5 3.5 0 0 1 7 0v7.75M15 12a2 2 0 1 0 4 0a2 2 0 1 0-4 0Zm-.5 9.5v-2.25a2.5 2.5 0 0 1 5 0v2.25m-8-5.5l3.25 2.25");
}

</style>
