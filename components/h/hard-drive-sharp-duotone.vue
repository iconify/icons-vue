<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="gp_8x1bzb"><path class="i4hho8ioh"/><path class="wt2sl3biy"/><path clip-rule="evenodd" class="nuq8w1bat"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:hard-drive-sharp-duotone" /></template>
<style>
.gp_8x1bzb {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.i4hho8ioh {
  stroke-opacity: 0.4;
  d: path("M2 11L5 4L19 4L22 11");
}

.nuq8w1bat {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M2 10L22 10C22.5523 10 23 10.4477 23 11L23 20C23 20.5523 22.5523 21 22 21L2 21C1.4477 21 1 20.5523 1 20L1 11C1 10.4477 1.4477 10 2 10ZM19 15.5C19 14.6716 18.3284 14 17.5 14C16.6716 14 16 14.6716 16 15.5C16 16.3284 16.6716 17 17.5 17C18.3284 17 19 16.3284 19 15.5Z");
  stroke: none;
}

.wt2sl3biy {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M19 15.5C19 16.3284 18.3284 17 17.5 17C16.6716 17 16 16.3284 16 15.5C16 14.6716 16.6716 14 17.5 14C18.3284 14 19 14.6716 19 15.5Z");
  stroke: none;
}

</style>
