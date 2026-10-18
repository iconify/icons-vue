<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="t5pz43ypy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:arrow-u-turn-left-line-flip-sharp" /></template>
<style>
.t5pz43ypy {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M9 5L12 5C14.7614 5 17 7.2386 17 10C17 12.7614 14.7614 15 12 15L3.3753 15M8.2739 19.2191L3 15L8.3753 10.6998M21 21L21 3");
}

</style>
