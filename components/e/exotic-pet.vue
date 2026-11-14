<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="o57t6ibrl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:exotic-pet" /></template>
<style>
.o57t6ibrl {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M8.5 13c2-2 5.5-2.5 8-2.25c1-1.25 3.5-1.75 5 .25c.5 1 0 2.75-1.5 3.25c-2.5.5-6 .5-8.5.5c-1.5 0-2.5-.75-3-1.75m0 0c-3 .5-5.5-1-5.5-4c0-2.75 3.25-4 4.75-2.25C9 8.25 7.75 10 6.25 9.5m-3.75 8h19m-6 0l1.25-2.75L18 17.5m-8 0l1.25-2.75l1.25 2.75m7-5.5h.01");
}

</style>
