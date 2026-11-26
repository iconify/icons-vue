<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="ts8ypqb9a"/><path class="pwybjynjx"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:flow-off-page-two-tone" /></template>
<style>
.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.pwybjynjx {
  d: path("M5 5L19 5C20.6569 5 22 6.3431 22 8L22 11C22 11.6295 21.7036 12.2223 21.2 12.6L13.2 18.6C12.4889 19.1333 11.5111 19.1333 10.8 18.6L2.8 12.6C2.2964 12.2223 2 11.6295 2 11L2 8C2 6.3431 3.3431 5 5 5Z");
}

.ts8ypqb9a {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M12 4L19 4C21.2092 4 23 5.7908 23 8L23 11C23 11.9443 22.5554 12.8334 21.8 13.4L13.8 19.4C12.7333 20.2 11.2667 20.2 10.2 19.4L2.2 13.4C1.4446 12.8334 1 11.9443 1 11L1 8C1 5.7908 2.7908 4 5 4Z");
  stroke: none;
}

</style>
