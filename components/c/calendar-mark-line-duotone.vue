<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><circle class="w7vm2wbzu"/><path class="gcjr-xbce"/><path class="p8if-j44r"/><path class="z8asjk3rx"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:calendar-mark-line-duotone" /></template>
<style>
.gcjr-xbce {
  d: path("M10 21.75H14C17.7712 21.75 19.6569 21.75 20.8284 20.5784C22 19.4069 22 17.5212 22 13.75V11.75C22 7.97876 22 6.09315 20.8284 4.92157C19.6569 3.75 17.7712 3.75 14 3.75H10C6.22876 3.75 4.34315 3.75 3.17157 4.92157C2 6.09315 2 7.97876 2 11.75V13.75C2 17.5212 2 19.4069 3.17157 20.5784C4.34315 21.75 6.22876 21.75 10 21.75Z");
}

.ipq1z-bjh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.p8if-j44r {
  d: path("M2.03516 8.75H21.965");
  opacity: var(--svg-opacity--0-5, 0.5);
}

.w7vm2wbzu {
  cx: 16.5px;
  cy: 16.5px;
  r: 1.5px;
}

.z8asjk3rx {
  d: path("M7 3.78496V2.25M17 3.78496V2.25");
  opacity: var(--svg-opacity--0-5, 0.5);
}

</style>
