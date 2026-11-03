<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="gp_8x1bzb"><path clip-rule="evenodd" class="f4zowo96l"/><path class="jg-48xb-u"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:concierge-bell-sharp-fill" /></template>
<style>
.f4zowo96l {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M4.1482 10.5987C5.7406 7.7578 8.7434 5.9986 12.0002 5.9986C15.2571 5.9986 18.26 7.7579 19.8524 10.599C19.9078 10.7255 19.9364 10.862 19.9364 11.0001C19.9364 11.5524 19.4886 12.0001 18.9363 12L5.0641 12C4.5118 12.0001 4.064 11.5525 4.064 11.0002C4.064 10.862 4.0927 10.7253 4.1482 10.5987ZM2 14L22 14C22.5523 14 23 14.4477 23 15L23 21C23 21.5523 22.5523 22 22 22L2 22C1.4477 22 1 21.5523 1 21L1 15C1 14.4477 1.4477 14 2 14Z");
  stroke: none;
}

.gp_8x1bzb {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.jg-48xb-u {
  d: path("M12 7L12 3M8 3L16 3");
}

</style>
