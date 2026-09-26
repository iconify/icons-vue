<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="gp_8x1bzb"><path class="e9e3jt7fz"/><path class="o7v31mbxc"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:arrow-big-down-sharp-two-tone" /></template>
<style>
.e9e3jt7fz {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M11.2929 22.7071L3.2929 14.7071C3.0069 14.4211 2.9213 13.991 3.0761 13.6173C3.2309 13.2436 3.5955 13 4 13L7 13L7 2C7 1.4477 7.4477 1 8 1L16 1C16.5523 1 17 1.4477 17 2L17 13L20 13C20.4045 13 20.7691 13.2436 20.9239 13.6173C21.0787 13.991 20.9931 14.4211 20.7071 14.7071L12.7071 22.7071C12.3166 23.0976 11.6834 23.0976 11.2929 22.7071Z");
  stroke: none;
}

.gp_8x1bzb {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.o7v31mbxc {
  d: path("M12 22L4 14L8 14L8 2L16 2L16 14L20 14Z");
}

</style>
