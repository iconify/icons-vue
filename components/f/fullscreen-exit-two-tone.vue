<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="lq48qtbtv"/><path class="ldnrvyb3m"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:fullscreen-exit-two-tone" /></template>
<style>
.ldnrvyb3m {
  d: path("M3 14L9.5 14C9.7761 14 10 14.2239 10 14.5L10 21M9.4 14.6L3 21");
}

.lq48qtbtv {
  stroke-opacity: 0.4;
  d: path("M21 10L14.5 10C14.2239 10 14 9.7761 14 9.5L14 3M14.6 9.4L21 3");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

</style>
