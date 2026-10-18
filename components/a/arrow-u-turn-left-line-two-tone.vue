<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ryaniwbkt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:arrow-u-turn-left-line-two-tone" /></template>
<style>
.ryaniwbkt {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M10 19L12 19C14.7614 19 17 16.7614 17 14C17 11.2386 14.7614 9 12 9L4 9M8 5L3.1877 8.6096C2.9375 8.8097 2.9375 9.1903 3.1877 9.3904L8 13M21 4L21 20");
}

</style>
