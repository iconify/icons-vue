<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="obdjf0fvg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:flip-2-vertical-sharp" /></template>
<style>
.obdjf0fvg {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M3 9L3 3L21 3L21 9M2 12L22 12M3 15L3 21L7 21M9.5 21L14.5 21M17 21L21 21L21 15");
}

</style>
