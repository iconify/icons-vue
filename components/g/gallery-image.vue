<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="sgv5ekbhx"/><path clip-rule="evenodd" class="l8fexdxtg"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:gallery-image" /></template>
<style>
.l8fexdxtg {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M15 11.5C15 12.33 14.3284 13 13.5 13C12.6716 13 12 12.33 12 11.5C12 10.67 12.6716 10 13.5 10C14.3284 10 15 10.67 15 11.5Z");
  stroke: none;
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.sgv5ekbhx {
  d: path("M5 3H19M21 18.38L17.9199 15.3C17.3921 14.77 16.5564 14.71 15.9592 15.16L14.0408 16.6C13.4436 17.05 12.6079 16.99 12.0801 16.46L10.0607 14.44C9.4749 13.85 8.5251 13.85 7.9393 14.44L3.3787 19M5 7H19C20.1046 7 21 7.9 21 9V19C21 20.1 20.1046 21 19 21H5C3.8954 21 3 20.1 3 19V9C3 7.9 3.8954 7 5 7Z");
}

</style>
