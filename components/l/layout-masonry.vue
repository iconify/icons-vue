<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="j3ny8wb7f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:layout-masonry" /></template>
<style>
.j3ny8wb7f {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M5.625 3h2.25A2.625 2.625 0 0 1 10.5 5.625v4.75A2.625 2.625 0 0 1 7.875 13h-2.25A2.625 2.625 0 0 1 3 10.375v-4.75A2.625 2.625 0 0 1 5.625 3M5.5 16H8a2.5 2.5 0 0 1 2.5 2.5A2.5 2.5 0 0 1 8 21H5.5A2.5 2.5 0 0 1 3 18.5A2.5 2.5 0 0 1 5.5 16M16 3h2.5A2.5 2.5 0 0 1 21 5.5A2.5 2.5 0 0 1 18.5 8H16a2.5 2.5 0 0 1-2.5-2.5A2.5 2.5 0 0 1 16 3m.125 8h2.25A2.625 2.625 0 0 1 21 13.625v4.75A2.625 2.625 0 0 1 18.375 21h-2.25a2.625 2.625 0 0 1-2.625-2.625v-4.75A2.625 2.625 0 0 1 16.125 11");
}

</style>
