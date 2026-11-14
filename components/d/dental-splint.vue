<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vdasbhb8i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:dental-splint" /></template>
<style>
.vdasbhb8i {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.5 8.75V6.5a2.25 2.25 0 0 1 4.5 0v2.25m-4.5 4.5l1.25 5.5a1 1 0 0 0 2 0L7 13.25m2.75-4.5V6.5a2.25 2.25 0 0 1 4.5 0v2.25m-4.5 4.5l1.25 5.5a1 1 0 0 0 2 0l1.25-5.5M17 8.75V6.5a2.25 2.25 0 0 1 4.5 0v2.25m-4.5 4.5l1.25 5.5a1 1 0 0 0 2 0l1.25-5.5m-19-4.5h19v4.5h-19Z");
}

</style>
