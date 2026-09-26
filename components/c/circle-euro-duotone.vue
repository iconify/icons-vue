<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="g2u3clbzs"/><path class="w5d_0sh3n"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:circle-euro-duotone" /></template>
<style>
.g2u3clbzs {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M12 1C18.0753 1 23 5.9247 23 12C23 18.0753 18.0753 23 12 23C5.9247 23 1 18.0753 1 12C1 5.9247 5.9247 1 12 1Z");
  stroke: none;
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.w5d_0sh3n {
  d: path("M15.8 16.8C14.7614 17.5789 13.4982 18 12.2 18C8.8863 18 6.2 15.3137 6.2 12C6.2 8.6863 8.8863 6 12.2 6C13.4982 6 14.7614 6.4211 15.8 7.2M6 10L14.2 10M6 14L14.2 14");
}

</style>
