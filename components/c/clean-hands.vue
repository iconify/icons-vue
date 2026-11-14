<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="aophy0n_e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:clean-hands" /></template>
<style>
.aophy0n_e {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M8 21c-2.5-1.5-3.5-4-3.5-6.5v-8a2 2 0 0 1 4 0v-2a2 2 0 0 1 4 0V11l2-2a2 2 0 0 1 3 2.5l-3.5 5q-1.5 2.25-1.5 4.5m-4-14.5V11m10-8.5l.884 1.616L21 5l-1.616.884L18.5 7.5l-.884-1.616L16 5l1.616-.884Z");
}

</style>
