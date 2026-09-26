<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="ur5we9b1t"/><path class="ux16gjr2e"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:book-x-fill" /></template>
<style>
.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.ur5we9b1t {
  fill: currentColor;
  d: path("M7 1L17 1C19.2091 1 21 2.7909 21 5L21 12C21 12.5523 20.5523 13 20 13L14 13C12.3431 13 11 14.3431 11 16L11 22C11 22.5523 10.5523 23 10 23L6 23C4.3431 23 3 21.6569 3 20L3 5C3 2.7909 4.7909 1 7 1ZM6 19C5.4477 19 5 19.4477 5 20C5 20.5523 5.4477 21 6 21L11 21L11 19L6 19ZM8 5C7.4477 5 7 5.4477 7 6L7 14C7 14.5523 7.4477 15 8 15C8.5523 15 9 14.5523 9 14L9 6C9 5.4477 8.5523 5 8 5Z");
  stroke: none;
}

.ux16gjr2e {
  d: path("M14 16L20 22M20 16L14 22");
}

</style>
