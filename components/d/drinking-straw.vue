<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lo8gkybsz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:drinking-straw" /></template>
<style>
.lo8gkybsz {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M19.425 4.575za1.5 1.5 0 0 1 0 2.122L6.697 19.425a1.5 1.5 0 0 1-2.122 0a1.5 1.5 0 0 1 0-2.122L17.303 4.575a1.5 1.5 0 0 1 2.122 0m-4.95 2.829l.707 3.535m-3.536-.707l.708 3.536m-3.536-.707l.707 3.535");
}

</style>
