<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="cs0sw7u1u"/><path class="llz1qlyol"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:hockey-puck-two-tone" /></template>
<style>
.cs0sw7u1u {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M19.4424 18.7569C17.4878 19.5388 14.8561 20 12 20C9.1439 20 6.5122 19.5388 4.5576 18.7569C3.583 18.3671 2.7272 17.8779 2.0988 17.2835C1.4682 16.6872 1 15.9158 1 15L1 9C1 8.0842 1.4682 7.3128 2.0988 6.7165C2.7272 6.1221 3.583 5.6329 4.5576 5.2431C6.5122 4.4612 9.1439 4 12 4C14.8561 4 17.4878 4.4612 19.4424 5.2431C20.417 5.6329 21.2728 6.1221 21.9012 6.7165C22.5318 7.3128 23 8.0842 23 9L23 15C23 15.9158 22.5318 16.6872 21.9012 17.2835C21.2728 17.8779 20.417 18.3671 19.4424 18.7569Z");
  stroke: none;
}

.llz1qlyol {
  d: path("M22 9C22 11.2091 17.5228 13 12 13C6.4772 13 2 11.2091 2 9C2 6.7909 6.4772 5 12 5C17.5228 5 22 6.7909 22 9ZM2 9L2 15C2 17.2091 6.4772 19 12 19C17.5228 19 22 17.2091 22 15L22 9");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

</style>
