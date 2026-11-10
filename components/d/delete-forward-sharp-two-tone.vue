<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="gp_8x1bzb"><path class="my40j6stq"/><path class="g-8xnhb3g"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:delete-forward-sharp-two-tone" /></template>
<style>
.g-8xnhb3g {
  d: path("M13.293 8.71L10 12M10 12L6.707 15.29M10 12L6.707 8.71M10 12L13.293 15.29M22 12L15 4H2V20H15L22 12Z");
}

.gp_8x1bzb {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.my40j6stq {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M15 3C15.288 3 15.563 3.12 15.753 3.34L22.753 11.34C23.082 11.72 23.082 12.28 22.753 12.66L15.753 20.66C15.563 20.88 15.288 21 15 21H2C1.448 21 1 20.55 1 20V4C1 3.45 1.448 3 2 3H15Z");
  stroke: none;
}

</style>
