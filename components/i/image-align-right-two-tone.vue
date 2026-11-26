<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="sc5errbsq"/><path class="lhx6wm3-w"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:image-align-right-two-tone" /></template>
<style>
.lhx6wm3-w {
  d: path("M13 7L19 7C20.1046 7 21 7.8954 21 9L21 15C21 16.1046 20.1046 17 19 17L13 17C11.8954 17 11 16.1046 11 15L11 9C11 7.8954 11.8954 7 13 7ZM3 3H21M3 21H21");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.sc5errbsq {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M16 6L19 6C20.6569 6 22 7.3431 22 9L22 15C22 16.6569 20.6569 18 19 18L13 18C11.3431 18 10 16.6569 10 15L10 9C10 7.3431 11.3431 6 13 6Z");
  stroke: none;
}

</style>
