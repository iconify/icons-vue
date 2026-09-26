<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="gp_8x1bzb"><path class="vbuzuybam"/><path class="bkois7buo"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:arrow-big-right-sharp-two-tone" /></template>
<style>
.bkois7buo {
  d: path("M22 12L14 20L14 16L2 16L2 8L14 8L14 4Z");
}

.gp_8x1bzb {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.vbuzuybam {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M22.7071 12.7071L14.7071 20.7071C14.4211 20.9931 13.991 21.0787 13.6173 20.9239C13.2436 20.7691 13 20.4045 13 20L13 17L2 17C1.4477 17 1 16.5523 1 16L1 8C1 7.4477 1.4477 7 2 7L13 7L13 4C13 3.5955 13.2436 3.2309 13.6173 3.0761C13.991 2.9213 14.4211 3.0069 14.7071 3.2929L22.7071 11.2929C23.0976 11.6834 23.0976 12.3166 22.7071 12.7071Z");
  stroke: none;
}

</style>
