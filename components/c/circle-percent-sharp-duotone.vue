<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="gp_8x1bzb"><path class="qbcs2xgch"/><path class="r0knw1b4v"/><path class="n0kzgsfmm"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:circle-percent-sharp-duotone" /></template>
<style>
.gp_8x1bzb {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.n0kzgsfmm {
  d: path("M7.7071 16.2929L16.2929 7.7071");
}

.qbcs2xgch {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M12 1C17.9372 1 23 6.0628 23 12C23 17.9372 17.9372 23 12 23C6.0628 23 1 17.9372 1 12C1 6.0628 6.0628 1 12 1Z");
  stroke: none;
}

.r0knw1b4v {
  fill: currentColor;
  d: path("M8.5 7C9.3285 7 10 7.6716 10 8.5C10 9.3285 9.3285 10 8.5 10C7.6716 10 7 9.3285 7 8.5C7 7.6716 7.6716 7 8.5 7ZM15.5 14C16.3285 14 17 14.6716 17 15.5C17 16.3285 16.3285 17 15.5 17C14.6716 17 14 16.3285 14 15.5C14 14.6716 14.6716 14 15.5 14Z");
  stroke: none;
}

</style>
