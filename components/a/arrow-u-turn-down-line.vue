<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="m8j67mb3h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:arrow-u-turn-down-line" /></template>
<style>
.m8j67mb3h {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M5 14L5 12C5 9.2386 7.2386 7 10 7C12.7614 7 15 9.2386 15 12L15 20M19 16L15.3904 20.8123C15.1903 21.0625 14.8097 21.0625 14.6096 20.8123L11 16M20 3L4 3");
}

</style>
