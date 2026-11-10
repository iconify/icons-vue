<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="gp_8x1bzb"><path class="r5zm8u7aq"/><path class="l2x7t_bvh"/><path clip-rule="evenodd" class="lo2a_abmw"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:guesthouse-sharp-two-tone" /></template>
<style>
.gp_8x1bzb {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.l2x7t_bvh {
  d: path("M3.998 2V4.8M3.998 4.8V17H19.998V3.2M22.928 3L19.998 3.2L3.998 4.8M3.998 4.8L1.098 5.09M9.998 17V14C9.998 12.9 10.894 12 11.998 12C13.103 12 13.998 12.9 13.998 14V17M8.998 21H14.998");
}

.lo2a_abmw {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M9 9C9 9.55 8.552 10 8 10C7.448 10 7 9.55 7 9C7 8.45 7.448 8 8 8C8.552 8 9 8.45 9 9Z");
  stroke: none;
}

.r5zm8u7aq {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M15 22H9V20H15V22ZM22.998 4L21 4.13V17C21 17.55 20.552 18 20 18H4C3.448 18 3 17.55 3 17V5.91L1.199 6.09L1 4.1L3 3.9V2H5V3.69L19.9 2.21L20 3.2L19.931 2.2L22.86 2L22.998 4Z");
  stroke: none;
}

</style>
