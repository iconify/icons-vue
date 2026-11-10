<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="m35y53q-k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:hanger-sharp" /></template>
<style>
.m35y53q-k {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M7 8V7C7 4.79 8.791 3 11 3C13.209 3 15 4.79 15 7C15 8.61 13.5 10 12 11L11.5 11.5M12 10.98L3 21H21L12 10.98Z");
}

</style>
