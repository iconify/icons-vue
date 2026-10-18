<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="smopympch"/><path class="lhx8w-bzb"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:diamond-two-tone" /></template>
<style>
.lhx8w-bzb {
  d: path("M10.5858 2.5858C10.9609 2.2107 11.4696 2 12 2C12.5304 2 13.0391 2.2107 13.4142 2.5858L21.4142 10.5858C21.7893 10.9609 22 11.4696 22 12C22 12.5304 21.7893 13.0391 21.4142 13.4142L13.4142 21.4142C13.0391 21.7893 12.5304 22 12 22C11.4696 22 10.9609 21.7893 10.5858 21.4142L2.5858 13.4142C2.2107 13.0391 2 12.5304 2 12C2 11.4696 2.2107 10.9609 2.5858 10.5858L10.5858 2.5858Z");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.smopympch {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M9.8787 1.8787C10.4413 1.3161 11.2044 1 12 1C12.7956 1 13.5587 1.3161 14.1213 1.8787L22.1213 9.8787C22.6839 10.4413 23 11.2044 23 12C23 12.7956 22.6839 13.5587 22.1213 14.1213L14.1213 22.1213C13.5587 22.6839 12.7956 23 12 23C11.2044 23 10.4413 22.6839 9.8787 22.1213L1.8787 14.1213C1.3161 13.5587 1 12.7956 1 12C1 11.2044 1.3161 10.4413 1.8787 9.8787L9.8787 1.8787Z");
  stroke: none;
}

</style>
