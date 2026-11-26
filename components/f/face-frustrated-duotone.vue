<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="cwinfwbnk"/><path class="wjx6sjbty"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:face-frustrated-duotone" /></template>
<style>
.cwinfwbnk {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M19.7782 4.2218C21.7677 6.2114 23 8.9627 23 12C23 18.0751 18.0751 23 12 23C5.9249 23 1 18.0751 1 12C1 5.9249 5.9249 1 12 1C15.0373 1 17.7886 2.2323 19.7782 4.2218Z");
  stroke: none;
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.wjx6sjbty {
  d: path("M7.5 8.5L10 10L7.5 11.5M16.5 8.5L14 10L16.5 11.5M9 16L15 16");
}

</style>
