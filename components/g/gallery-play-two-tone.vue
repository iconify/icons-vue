<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="rejck-vqi"/><path class="l7vg9yb8o"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:gallery-play-two-tone" /></template>
<style>
.l7vg9yb8o {
  d: path("M5 3H19M5 7H19C20.1046 7 21 7.9 21 9V19C21 20.1 20.1046 21 19 21H5C3.8954 21 3 20.1 3 19V9C3 7.9 3.8954 7 5 7ZM9.5 11.77C9.5 11.17 10.1106 10.8 10.5813 11.12L14.3339 13.67C14.5554 13.82 14.5554 14.18 14.3339 14.33L10.5813 16.88C10.1106 17.2 9.5 16.83 9.5 16.23V11.77Z");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.rejck-vqi {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M19 6C20.6569 6 22 7.34 22 9V19C22 20.66 20.6569 22 19 22H5C3.3432 22 2 20.66 2 19V9C2 7.34 3.3431 6 5 6H19ZM19 2C19.5523 2 20 2.45 20 3C20 3.55 19.5523 4 19 4H5C4.4477 4 4 3.55 4 3C4 2.45 4.4477 2 5 2H19Z");
  stroke: none;
}

</style>
