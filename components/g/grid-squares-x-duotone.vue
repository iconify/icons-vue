<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="qbwvuyb5c"/><path class="s4y-3xbwz"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:grid-squares-x-duotone" /></template>
<style>
.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.qbwvuyb5c {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M2 16C2 14.3431 3.3431 13 5 13L8 13C9.6569 13 11 14.3431 11 16L11 19C11 20.6569 9.6569 22 8 22L5 22C3.3431 22 2 20.6569 2 19L2 16ZM2 5C2 3.3431 3.3431 2 5 2L8 2C9.6569 2 11 3.3431 11 5L11 8C11 9.6569 9.6569 11 8 11L5 11C3.3431 11 2 9.6569 2 8L2 5ZM13 5C13 3.3431 14.3431 2 16 2L19 2C20.6569 2 22 3.3431 22 5L22 8C22 9.6569 20.6569 11 19 11L16 11C14.3431 11 13 9.6569 13 8L13 5Z");
  stroke: none;
}

.s4y-3xbwz {
  d: path("M15 15L20 20M20 15L15 20");
}

</style>
