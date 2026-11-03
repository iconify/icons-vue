<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path clip-rule="evenodd" class="b8za7gb0j"/><path class="nrtjvzb2k"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:desk-office-two-tone" /></template>
<style>
.b8za7gb0j {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  fill-rule: evenodd;
  d: path("M14 11L20 11C21.1046 11 22 11.8954 22 13L22 21C22 22.1046 21.1046 23 20 23L15 23C13.8954 23 13 22.1046 13 21L13 12C13 11.4477 13.4477 11 14 11ZM12 9L8.5 9C7.1193 9 6 7.8807 6 6.5L6 3.5C6 2.1193 7.1193 1 8.5 1L15.5 1C16.8807 1 18 2.1193 18 3.5L18 6.5C18 7.8807 16.8807 9 15.5 9L12 9Z");
  stroke: none;
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.nrtjvzb2k {
  d: path("M3 22L3 13C3 12.4477 3.4477 12 4 12L20 12C20.5523 12 21 12.4477 21 13L21 21C21 21.5523 20.5523 22 20 22L15 22C14.4477 22 14 21.5523 14 21L14 12M21 17L14 17M12 12L12 8M12 8L8.5 8C7.6716 8 7 7.3284 7 6.5L7 3.5C7 2.6716 7.6716 2 8.5 2L15.5 2C16.3284 2 17 2.6716 17 3.5L17 6.5C17 7.3284 16.3284 8 15.5 8Z");
}

</style>
