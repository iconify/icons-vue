<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="shdjazrjw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:commute-time" /></template>
<style>
.shdjazrjw {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M16.75 2.5h3a1.75 1.75 0 0 1 1.75 1.75v6.5a1.75 1.75 0 0 1-1.75 1.75h-3A1.75 1.75 0 0 1 15 10.75v-6.5a1.75 1.75 0 0 1 1.75-1.75m1.5 3h.01M18.25 9h.01M3 21.5c2-4.5 7-6 12.5-7m-2.5 7c1-3.5 3.5-6 6.5-7m-11 5l1.75-1.5");
}

</style>
