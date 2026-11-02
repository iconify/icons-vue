<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="f6-773fhv"/><path class="kf_vmnxdo"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:google-duotone-round" /></template>
<style>
.f6-773fhv {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-2, 0.2);
  d: path("m18.33 5.746l-2.655 2.392a1 1 0 0 1-1.216.094A4.5 4.5 0 1 0 15.354 15H13a1 1 0 0 1-1-1v-3a1 1 0 0 1 1-1h7.944a1 1 0 0 1 .994.889Q22 11.442 22 12a10 10 0 0 1-8.017 9.801a9.996 9.996 0 0 1-11.197-5.908a10.03 10.03 0 0 1 0-7.786A9.99 9.99 0 0 1 12 2a9.9 9.9 0 0 1 3.336.573a9.9 9.9 0 0 1 2.954 1.653a1 1 0 0 1 .04 1.52");
}

.ft5dv1b6b {
  fill: none;
}

.kf_vmnxdo {
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M20.944 11H13v3h4.123m0 0a5.5 5.5 0 1 1-2.117-6.605l2.655-2.392A9 9 0 0 0 3 12a9 9 0 0 0 9 9a9 9 0 0 0 8.944-10");
}

</style>
