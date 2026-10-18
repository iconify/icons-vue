<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="dk166sbrq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:arrow-u-turn-right-line-flip-sharp-two-tone" /></template>
<style>
.dk166sbrq {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M15 5L12 5C9.2386 5 7 7.2386 7 10C7 12.7614 9.2386 15 12 15L20.6247 15M15.7261 19.2191L21 15L15.6247 10.6998M3 21L3 3");
}

</style>
