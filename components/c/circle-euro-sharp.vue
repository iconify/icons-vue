<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="gp_8x1bzb"><path class="uk-eumb3f"/><path class="a_oiwebeh"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:circle-euro-sharp" /></template>
<style>
.a_oiwebeh {
  d: path("M16.2 16.5L15.8 16.8C14.7614 17.5789 13.4982 18 12.2 18C8.8863 18 6.2 15.3137 6.2 12C6.2 8.6863 8.8863 6 12.2 6C13.4982 6 14.7614 6.4211 15.8 7.2L16.2 7.5M5 10L6 10L14.2 10L15.2 10M5 14L6 14L14.2 14L15.2 14");
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
