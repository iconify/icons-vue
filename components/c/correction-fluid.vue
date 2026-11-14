<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="tow8m-boo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:correction-fluid" /></template>
<style>
.tow8m-boo {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M9.625 9h4.75A2.625 2.625 0 0 1 17 11.625v7.25a2.625 2.625 0 0 1-2.625 2.625h-4.75A2.625 2.625 0 0 1 7 18.875v-7.25A2.625 2.625 0 0 1 9.625 9m1.125-4.5h2.5A1.75 1.75 0 0 1 15 6.25v1A1.75 1.75 0 0 1 13.25 9h-2.5A1.75 1.75 0 0 1 9 7.25v-1a1.75 1.75 0 0 1 1.75-1.75M9.5 14h5");
}

</style>
