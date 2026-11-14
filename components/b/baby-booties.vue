<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rb587qb5w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:baby-booties" /></template>
<style>
.rb587qb5w {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M4 4.5h1.25A1.5 1.5 0 0 1 6.75 6a1.5 1.5 0 0 1-1.5 1.5H4A1.5 1.5 0 0 1 2.5 6A1.5 1.5 0 0 1 4 4.5m-1.5 3v10c0 1.25.75 2 2 2H9c1 0 1.5-.75 1.5-1.5c0-1.75-1.25-3-3.25-3.25h-.5V7.5m8.25-3h1.25a1.5 1.5 0 0 1 1.5 1.5a1.5 1.5 0 0 1-1.5 1.5H15A1.5 1.5 0 0 1 13.5 6A1.5 1.5 0 0 1 15 4.5m-1.5 3v10c0 1.25.75 2 2 2H20c1 0 1.5-.75 1.5-1.5c0-1.75-1.25-3-3.25-3.25h-.5V7.5");
}

</style>
