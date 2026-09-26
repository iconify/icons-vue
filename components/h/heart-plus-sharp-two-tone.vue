<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="gp_8x1bzb"><path class="qlh6dmbhz"/><path class="t1liywete"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:heart-plus-sharp-two-tone" /></template>
<style>
.gp_8x1bzb {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.qlh6dmbhz {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M11.3505 21.7604C6.8469 17.9139 1 14.3082 1 8.75C1 5.1476 4.2844 2 8 2C9.4261 2 10.8308 2.479 12 3.2568C13.1692 2.479 14.5739 2 16 2C19.7156 2 23 5.1476 23 8.75C23 9.6569 22.8454 10.5123 22.5653 11.3247L22.3334 12L13 12L13 20.3972L11.6311 22L11.3505 21.7604Z");
  stroke: none;
}

.t1liywete {
  d: path("M21.3876 11.6753L21.6195 11C21.8649 10.2852 22 9.538 22 8.75C22 5.5743 19.3138 3 16 3C14.5 3 13.1574 3.5459 12 4.5C10.8426 3.5459 9.5 3 8 3C4.6862 3 2 5.5743 2 8.75C2 13.75 7.4376 17.1033 12 21L12.2805 21.2396M19 14L19 22M15 18L23 18");
}

</style>
