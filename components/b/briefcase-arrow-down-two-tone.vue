<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="fbu92db-w"/><path class="wvbwwsbvy"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:briefcase-arrow-down-two-tone" /></template>
<style>
.fbu92db-w {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M16.5 5L18 5C20.2092 5 22 6.7908 22 9L22 15C22 17.2092 20.2092 19 18 19L6 19C3.7908 19 2 17.2092 2 15L2 9C2 6.7908 3.7908 5 6 5L7.5 5C7.5 2.7908 9.2908 1 11.5 1L12.5 1C14.7092 1 16.5 2.7908 16.5 5Z");
  stroke: none;
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.wvbwwsbvy {
  d: path("M12 10L12 14M9 11L12 14L15 11M3 22L21 22M8.5 6L6 6C4.3431 6 3 7.3431 3 9L3 15C3 16.6569 4.3431 18 6 18L18 18C19.6569 18 21 16.6569 21 15L21 9C21 7.3431 19.6569 6 18 6L15.5 6M8.5 6L8.5 5C8.5 3.3431 9.8431 2 11.5 2L12.5 2C14.1569 2 15.5 3.3431 15.5 5L15.5 6M8.5 6L15.5 6");
}

</style>
