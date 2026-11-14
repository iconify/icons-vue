<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xit4mbb4w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:goal-light" /></template>
<style>
.xit4mbb4w {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M7 15.5v-3a5 5 0 0 1 10 0v3Zm-.25 0h10.5A1.75 1.75 0 0 1 19 17.25v.5a1.75 1.75 0 0 1-1.75 1.75H6.75A1.75 1.75 0 0 1 5 17.75v-.5a1.75 1.75 0 0 1 1.75-1.75M12 4v2M4.5 7L6 8.5M19.5 7L18 8.5");
}

</style>
