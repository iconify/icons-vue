<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="i8cw80bwo"/><path class="ap87rxbvt"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:crystal-ball-duotone" /></template>
<style>
.ap87rxbvt {
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M7 17C1.262 12.302 4.584 3 12 3s10.738 9.302 5 14M5 18a1 1 0 0 1 1-1h12a1 1 0 0 1 1 1v2a1 1 0 0 1-1 1H6a1 1 0 0 1-1-1Zm4-8a3 3 0 0 1 3-3");
}

.ft5dv1b6b {
  fill: none;
}

.i8cw80bwo {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-2, 0.2);
  d: path("M7 17C1.266 12.293 4.581 3.009 12 3c7.419.009 10.734 9.293 5 14h1c.55 0 1 .45 1 1v2c0 .55-.45 1-1 1H6c-.55 0-1-.45-1-1v-2c0-.55.45-1 1-1Z");
}

</style>
