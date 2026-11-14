<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="f6xnkab9m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:baseball-pitcher" /></template>
<style>
.f6xnkab9m {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M7.25 4.25a1.75 1.75 0 1 0 3.5 0a1.75 1.75 0 1 0-3.5 0ZM6 21.5l4.5-7l6 7M9.25 8.75l1.25 5.75M4 12l5.5-2.5l5-3.5m2.75-1.5a2 2 0 1 0 4 0a2 2 0 1 0-4 0Z");
}

</style>
