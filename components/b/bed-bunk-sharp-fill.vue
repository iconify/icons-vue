<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="gp_8x1bzb"><path class="vb88b_k7z"/><path class="d-ud5o33i"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:bed-bunk-sharp-fill" /></template>
<style>
.d-ud5o33i {
  fill: currentColor;
  d: path("M6 4L3 4C2.4477 4 2 4.4477 2 5L2 9C2 9.5523 2.4477 10 3 10L9 10C9.5523 10 10 9.5523 10 9L10 5C10 4.4477 9.5523 4 9 4ZM6 12L3 12C2.4477 12 2 12.4477 2 13L2 17C2 17.5523 2.4477 18 3 18L9 18C9.5523 18 10 17.5523 10 17L10 13C10 12.4477 9.5523 12 9 12Z");
  stroke: none;
}

.gp_8x1bzb {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.vb88b_k7z {
  d: path("M3 5L9 5L9 9M3 13L9 13L9 17M16 13L21 13M3 22L3 17L3 15L3 13L3 9L3 7L3 5L3 2M21 9L16 9L9 9L3 9M21 17L16 17L9 17L3 17M16 22L16 21L16 20L16 17L16 13L16 9M21 2L21 5L21 9L21 13L21 17L21 22");
}

</style>
