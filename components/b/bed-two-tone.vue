<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="jh83o49ny"/><path class="s7zkpubbl"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:bed-two-tone" /></template>
<style>
.jh83o49ny {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M1 17L1 9L5 9L5 7C5 5.3431 6.3431 4 8 4L10 4C11.6569 4 13 5.3431 13 7L13 9L19 9C21.2091 9 23 10.7909 23 13L23 17L1 17Z");
  stroke: none;
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.s7zkpubbl {
  d: path("M2 4L2 20M2 10L19 10C20.6569 10 22 11.3431 22 13L22 16L2 16ZM6 10L6 7C6 5.8954 6.8954 5 8 5L10 5C11.1046 5 12 5.8954 12 7L12 10M22 16L22 20");
}

</style>
