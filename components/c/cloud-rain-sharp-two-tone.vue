<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="gp_8x1bzb"><path class="agq-vibiy"/><path class="labsonb6c"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:cloud-rain-sharp-two-tone" /></template>
<style>
.agq-vibiy {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M6 17L18 17C20.6233 17 23 14.6233 23 12C23 9.6937 21.163 7.578 18.9365 7.1004C18.4644 3.7612 15.4245 1 12 1C8.5755 1 5.5356 3.7612 5.0635 7.1004C2.837 7.578 1 9.6937 1 12C1 14.6233 3.3767 17 6 17Z");
  stroke: none;
}

.gp_8x1bzb {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.labsonb6c {
  d: path("M6 16L18 16C20.2091 16 22 14.2091 22 12C22 9.7909 20.2091 8 18 8C18 4.6863 15.3137 2 12 2C8.6863 2 6 4.6863 6 8C3.7909 8 2 9.7909 2 12C2 14.2091 3.7909 16 6 16ZM8 19L8 23M12 19L12 23M16 19L16 23");
}

</style>
