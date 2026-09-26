<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="gp_8x1bzb"><path class="ndowq2jxm"/><path class="vm8f6tbhw"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:arrow-big-left-short-sharp-two-tone" /></template>
<style>
.gp_8x1bzb {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.ndowq2jxm {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M2.2929 11.2929L12.2929 1.2929C12.5789 1.0069 13.009 0.9213 13.3827 1.0761C13.7564 1.2309 14 1.5955 14 2L14 6L21 6C21.5523 6 22 6.4477 22 7L22 17C22 17.5523 21.5523 18 21 18L14 18L14 22C14 22.4045 13.7564 22.7691 13.3827 22.9239C13.009 23.0787 12.5789 22.9931 12.2929 22.7071L2.2929 12.7071C1.9024 12.3166 1.9024 11.6834 2.2929 11.2929Z");
  stroke: none;
}

.vm8f6tbhw {
  d: path("M3 12L13 2L13 7L21 7L21 17L13 17L13 22Z");
}

</style>
