<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="nmiyghblf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:accountant-desk" /></template>
<style>
.nmiyghblf {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.5 12h19M5 12v9m14-9v9M7.125 3h2.75A2.625 2.625 0 0 1 12.5 5.625v3.75A2.625 2.625 0 0 1 9.875 12h-2.75A2.625 2.625 0 0 1 4.5 9.375v-3.75A2.625 2.625 0 0 1 7.125 3M7 6h3M7.25 9.25h.01m2.74 0h.01");
}

</style>
