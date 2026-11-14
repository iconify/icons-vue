<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="i1vsrd5on"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:ammonite" /></template>
<style>
.i1vsrd5on {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M21 13a9 9 0 0 0-18 0a7 7 0 0 0 14 0a5 5 0 0 0-10 0a3 3 0 0 0 6 0m-1-9v4m-2 8v4m7-7h4");
}

</style>
