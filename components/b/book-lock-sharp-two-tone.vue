<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="gp_8x1bzb"><path class="znicj9hvu"/><path class="onmj4dbxw"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:book-lock-sharp-two-tone" /></template>
<style>
.gp_8x1bzb {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.onmj4dbxw {
  d: path("M20 10L20 2L4 2L4 22M10 22L4 22L4 18L10 18M8 6L8 14M13 17L20 17L20 22L13 22ZM14.5 17L14.5 15C14.5 13.8954 15.3954 13 16.5 13C17.6046 13 18.5 13.8954 18.5 15L18.5 17");
}

.znicj9hvu {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M4 1L20 1C20.5523 1 21 1.4477 21 2L21 9C21 9.5523 20.5523 10 20 10L10 10L10 22C10 22.5523 9.5523 23 9 23L4 23C3.4477 23 3 22.5523 3 22L3 2C3 1.4477 3.4477 1 4 1Z");
  stroke: none;
}

</style>
