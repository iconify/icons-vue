<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="e-qm7acrz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:equal-approximately-duotone" /></template>
<style>
.e-qm7acrz {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M5 8.5C5.9123 7.5421 7.1772 7 8.5 7C9.8228 7 11.0877 7.5421 12 8.5C12.9123 9.4579 14.1772 10 15.5 10C16.8228 10 18.0877 9.4579 19 8.5M5 15.5C5.9123 14.5421 7.1772 14 8.5 14C9.8228 14 11.0877 14.5421 12 15.5C12.9123 16.4579 14.1772 17 15.5 17C16.8228 17 18.0877 16.4579 19 15.5");
}

</style>
