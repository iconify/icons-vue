<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="pqjc29d4q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:baptismal-font" /></template>
<style>
.pqjc29d4q {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M6 8a6 5 0 0 1 12 0M4 8h16l-2.5 4.5h-11Zm6 4.5v6m4-6v6m-5.75 0h7.5A1.25 1.25 0 0 1 17 19.75A1.25 1.25 0 0 1 15.75 21h-7.5A1.25 1.25 0 0 1 7 19.75a1.25 1.25 0 0 1 1.25-1.25");
}

</style>
