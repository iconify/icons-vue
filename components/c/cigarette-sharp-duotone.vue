<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="gp_8x1bzb"><path class="ftg773bui"/><path class="u0pvk3y4l"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:cigarette-sharp-duotone" /></template>
<style>
.ftg773bui {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M2 15L18 15C18.5523 15 19 15.4477 19 16L19 21C19 21.5523 18.5523 22 18 22L2 22C1.4477 22 1 21.5523 1 21L1 16C1 15.4477 1.4477 15 2 15Z");
  stroke: none;
}

.gp_8x1bzb {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.u0pvk3y4l {
  d: path("M22 15L22 22M19 12L13.5 12C11.0147 12 9 9.9853 9 7.5C9 5.6082 10.1832 3.9184 11.9609 3.2714L12.8723 2.9397M15 3L16 3C17.6569 3 19 4.3431 19 6L19 7.5C20.6569 7.5 22 8.8431 22 10.5L22 13M19 7.5L16.5 7.5");
}

</style>
