<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="gp_8x1bzb"><path class="tyv81fb_p"/><path class="eubqfrolr"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:circle-zap-sharp-duotone" /></template>
<style>
.eubqfrolr {
  d: path("M13.1111 7.0001L7.0001 13.1111L11.4444 13.1111L10.8889 16.9999L16.9999 10.8889L12.5556 10.8889L13.1111 7.0001Z");
}

.gp_8x1bzb {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.tyv81fb_p {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M23 12C23 17.937 17.937 23 12 23C6.063 23 1 17.937 1 12C1 6.063 6.063 1 12 1C17.937 1 23 6.063 23 12Z");
  stroke: none;
}

</style>
