<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="gp_8x1bzb"><path class="mxnhylz1j"/><path class="zgsw1b4mz"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:hourglass-sharp-duotone" /></template>
<style>
.gp_8x1bzb {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.mxnhylz1j {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M5 3L4 3L3 3L3 1L21 1L21 3L19 3L19 7C19 7.2968 18.8682 7.5782 18.6402 7.7682L13.562 12L18.6402 16.2318C18.8682 16.4218 19 16.7032 19 17L19 21L21 21L21 23L3 23L3 21L5 21L5 17C5 16.7032 5.1318 16.4218 5.3598 16.2318L10.438 12L5.3598 7.7682C5.1318 7.5782 5 7.2968 5 7Z");
  stroke: none;
}

.zgsw1b4mz {
  d: path("M3 2L21 2M3 22L21 22");
}

</style>
