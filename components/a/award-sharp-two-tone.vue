<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="gp_8x1bzb"><path class="rhsly9saa"/><path class="l8iufbc7b"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:award-sharp-two-tone" /></template>
<style>
.gp_8x1bzb {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.l8iufbc7b {
  d: path("M19 9C19 12.866 15.866 16 12 16C8.134 16 5 12.866 5 9C5 5.134 8.134 2 12 2C15.866 2 19 5.134 19 9ZM16.1787 14.6159L19 22L12 19.2077L5 22L7.8213 14.6159");
}

.rhsly9saa {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M19 9C19 12.866 15.866 16 12 16C8.134 16 5 12.866 5 9C5 5.134 8.134 2 12 2C15.866 2 19 5.134 19 9Z");
  stroke: none;
}

</style>
