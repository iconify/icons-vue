<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="gp_8x1bzb"><path class="a75ggrbaq"/><path class="vya7nrb2h"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:hard-hat-sharp-two-tone" /></template>
<style>
.a75ggrbaq {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M12 22L2 22C1.4477 22 1 21.5523 1 21L1 17C1 16.4477 1.4477 16 2 16L3 16L3 13C3 9.0803 5.5048 5.7479 9 4.5124L9 3C9 2.4477 9.4477 2 10 2L14 2C14.5523 2 15 2.4477 15 3L15 4.5124C18.4952 5.7479 21 9.0803 21 13L21 16L22 16C22.5523 16 23 16.4477 23 17L23 21C23 21.5523 22.5523 22 22 22Z");
  stroke: none;
}

.gp_8x1bzb {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.vya7nrb2h {
  d: path("M4 17L2 17L2 21L22 21L22 17L20 17M4 17L4 13C4 9.2723 6.5495 6.1401 10 5.252M4 17L10 17M20 17L20 13C20 9.2723 17.4505 6.1401 14 5.252M20 17L14 17M10 17L14 17M10 17L10 5.252M14 17L14 5.252M10 5.252L10 3L14 3L14 5.252");
}

</style>
