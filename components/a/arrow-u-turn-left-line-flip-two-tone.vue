<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wip53abyj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:arrow-u-turn-left-line-flip-two-tone" /></template>
<style>
.wip53abyj {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M10 5L12 5C14.7614 5 17 7.2386 17 10C17 12.7614 14.7614 15 12 15L4 15M8 19L3.1877 15.3904C2.9375 15.1903 2.9375 14.8097 3.1877 14.6096L8 11M21 20L21 4");
}

</style>
