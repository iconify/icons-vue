<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path clip-rule="evenodd" class="lp7pay4co"/><path class="z61d8ac9f"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:fire-extinguisher-fill" /></template>
<style>
.lp7pay4co {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M14.495 6.6662C16.0453 7.5585 17.0006 9.2112 17 11L17 19C17 20.6569 15.6569 22 14 22L10 22C8.3431 22 7 20.6569 7 19L7 11C6.9994 9.2112 7.9547 7.5585 9.505 6.6662C9.1756 6.173 8.9999 5.5932 8.9999 5.0001C8.9999 3.3432 10.3431 2 12 2C13.6569 2 15.0001 3.3432 15.0001 5.0001C15.0001 5.5932 14.8244 6.173 14.495 6.6662ZM9 15L9 17L15 17L15 15L9 15Z");
  stroke: none;
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.z61d8ac9f {
  d: path("M14 5L18 5M18 5L20 3M18 5L20 7M10 5C6.6863 5 4 7.6863 4 11L4 20M8 16L4 16");
}

</style>
