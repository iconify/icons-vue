<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="j4bn9tgvh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:fighter-jet" /></template>
<style>
.j4bn9tgvh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m12 2.5l1.5 6l7 7V17L14 16l1.25 3.5V21L12 20l-3.25 1v-1.5L10 16l-6.5 1v-1.5l7-7ZM12 7v3.5");
}

</style>
