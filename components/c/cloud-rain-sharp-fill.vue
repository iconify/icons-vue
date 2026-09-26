<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="gp_8x1bzb"><path class="e64exhbvl"/><path class="f08o8qcgp"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:cloud-rain-sharp-fill" /></template>
<style>
.e64exhbvl {
  fill: currentColor;
  d: path("M6 17L18 17C20.6233 17 23 14.6233 23 12C23 9.6937 21.163 7.578 18.9365 7.1004C18.4644 3.7612 15.4245 1 12 1C8.5755 1 5.5356 3.7612 5.0635 7.1004C2.837 7.578 1 9.6937 1 12C1 14.6233 3.3767 17 6 17Z");
  stroke: none;
}

.f08o8qcgp {
  d: path("M8 19L8 23M12 19L12 23M16 19L16 23");
}

.gp_8x1bzb {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

</style>
