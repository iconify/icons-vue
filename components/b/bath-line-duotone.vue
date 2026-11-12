<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="z6g8x2zmx"/><path class="y9_petz-w"/><path class="vz1kxy-md"/><path class="yirxaabex"/><path class="epc-37avp"/><path class="vz6h-5b6e"/><path class="ry2i6vb9v"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:bath-line-duotone" /></template>
<style>
.epc-37avp {
  d: path("M3 13V4.38516C3 3.06787 4.06787 2 5.38516 2C6.36047 2 7.23752 2.59379 7.59973 3.49934L8 4.38516");
  opacity: var(--svg-opacity--0-5, 0.5);
}

.ipq1z-bjh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.ry2i6vb9v {
  d: path("M6.34592 8.74162C6.03596 7.95499 6.01698 7.04309 6.36245 6.19238C6.68719 5.39271 7.27615 4.78944 7.97918 4.44719C8.77196 4.06126 9.70979 4.00726 10.5773 4.37789C11.3958 4.72754 11.9967 5.38891 12.3067 6.17554");
}

.vz1kxy-md {
  d: path("M18 20L19 22");
  opacity: var(--svg-opacity--0-5, 0.5);
}

.vz6h-5b6e {
  d: path("M12.3065 6.17554L6.3457 8.74162");
}

.y9_petz-w {
  d: path("M6 20L5 22");
  opacity: var(--svg-opacity--0-5, 0.5);
}

.yirxaabex {
  d: path("M2 12H22");
}

.z6g8x2zmx {
  d: path("M12 20.5C12.6493 20.5 13.364 20.4831 14.0982 20.4555C14.3558 20.4458 14.4845 20.441 14.7053 20.4186C17.983 20.0867 20.7773 17.1854 20.9859 13.8977C21 13.6762 21 13.4784 21 13.0827C21 13.0059 21 12.9675 20.9979 12.9351C20.9653 12.4339 20.5661 12.0347 20.0649 12.0021C20.0325 12 19.9941 12 19.9173 12H4.08268C4.00591 12 3.96752 12 3.93511 12.0021C3.43395 12.0347 3.0347 12.4339 3.00211 12.9351C3 12.9675 3 13.0059 3 13.0827C3 13.4784 3 13.6762 3.01406 13.8977C3.22272 17.1854 6.01705 20.0867 9.29467 20.4186C9.51545 20.441 9.64425 20.4458 9.90183 20.4555C10.636 20.4831 11.3507 20.5 12 20.5Z");
}

</style>
