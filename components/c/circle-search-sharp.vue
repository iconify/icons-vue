<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="gp_8x1bzb"><path class="uk-eumb3f"/><path class="aeo3abcnr"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:circle-search-sharp" /></template>
<style>
.aeo3abcnr {
  d: path("M13.391 13.39L16.535 16.535M14.357 11.057C14.357 12.88 12.88 14.357 11.057 14.357C9.235 14.357 7.757 12.88 7.757 11.057C7.757 9.235 9.235 7.757 11.057 7.757C12.88 7.757 14.357 9.235 14.357 11.057Z");
}

.gp_8x1bzb {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.uk-eumb3f {
  d: path("M12 2C17.523 2 22 6.477 22 12C22 17.523 17.523 22 12 22C6.477 22 2 17.523 2 12C2 6.477 6.477 2 12 2Z");
}

</style>
