<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="gp_8x1bzb"><path class="yghrljg0r"/><path class="li8c26bmd"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:bin-2-sharp-duotone" /></template>
<style>
.gp_8x1bzb {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.li8c26bmd {
  d: path("M9 2L15 2M3 7L21 7M10 10L10 19M14 10L14 19");
}

.yghrljg0r {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M5 6L19 6L19 22C19 22.5523 18.5523 23 18 23L6 23C5.4477 23 5 22.5523 5 22L5 6Z");
  stroke: none;
}

</style>
