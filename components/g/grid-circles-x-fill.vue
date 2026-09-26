<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="jc551fbod"/><path class="s4y-3xbwz"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:grid-circles-x-fill" /></template>
<style>
.jc551fbod {
  fill: currentColor;
  d: path("M6.5 13C8.9854 13 11 15.0147 11 17.5C11 19.9854 8.9854 22 6.5 22C4.0146 22 2 19.9854 2 17.5C2 15.0147 4.0146 13 6.5 13ZM6.5 2C8.9854 2 11 4.0146 11 6.5C11 8.9854 8.9854 11 6.5 11C4.0146 11 2 8.9854 2 6.5C2 4.0146 4.0146 2 6.5 2ZM17.5 2C19.9854 2 22 4.0146 22 6.5C22 8.9854 19.9854 11 17.5 11C15.0147 11 13 8.9854 13 6.5C13 4.0146 15.0147 2 17.5 2Z");
  stroke: none;
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.s4y-3xbwz {
  d: path("M15 15L20 20M20 15L15 20");
}

</style>
