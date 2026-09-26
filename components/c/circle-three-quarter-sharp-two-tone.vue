<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="gp_8x1bzb"><path class="e9ewmybae"/><path class="l-1ucdbni"/><path class="w4phe46dc"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:circle-three-quarter-sharp-two-tone" /></template>
<style>
.e9ewmybae {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M12 1C17.937 1 23 6.0629 23 12C23 17.937 17.937 23 12 23C6.0629 23 1 17.937 1 12C1 6.0629 6.0629 1 12 1Z");
  stroke: none;
}

.gp_8x1bzb {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.l-1ucdbni {
  d: path("M12 2C17.5228 2 22 6.4771 22 12C22 17.5228 17.5228 22 12 22C6.4771 22 2 17.5228 2 12C2 6.4771 6.4771 2 12 2Z");
}

.w4phe46dc {
  fill: currentColor;
  d: path("M12 5L12 12L5 12C5 13.3845 5.4105 14.7378 6.1797 15.889C6.9489 17.0401 8.0421 17.9373 9.3212 18.4672C10.6003 18.997 12.0078 19.1356 13.3656 18.8655C14.7235 18.5954 15.9708 17.9287 16.9497 16.9497C17.9287 15.9708 18.5954 14.7235 18.8655 13.3656C19.1356 12.0078 18.997 10.6003 18.4672 9.3212C17.9373 8.0421 17.0401 6.9489 15.889 6.1797C14.7378 5.4105 13.3845 5 12 5Z");
  stroke: none;
}

</style>
