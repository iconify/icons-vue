<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="gp_8x1bzb"><path class="e3c25sbbt"/><path class="x5xpiiefp"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:list-filter-x-sharp-duotone" /></template>
<style>
.e3c25sbbt {
  stroke-opacity: 0.4;
  d: path("M1 7L2 7L14 7L15 7");
}

.gp_8x1bzb {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.x5xpiiefp {
  d: path("M5 13L6 13L18 13L19 13M9 19L10 19L14 19L15 19M17.7071 4.7071L18 5L22 9L22.2929 9.2929M22.2929 4.7071L22 5L18 9L17.7071 9.2929");
}

</style>
