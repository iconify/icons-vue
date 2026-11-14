<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="h2qsadcrv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:altimeter" /></template>
<style>
.h2qsadcrv {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.5 12a9.5 9.5 0 1 0 19 0a9.5 9.5 0 1 0-19 0M12 2.5v2.25m8.25 2.5l-2 1.25m2 8.25l-2-1.25m-6.25 6v-2.25m-8.25-2.5l2-1.25m-2-8.25l2 1.25M12 12l2.75-2.75L13 11z");
}

</style>
