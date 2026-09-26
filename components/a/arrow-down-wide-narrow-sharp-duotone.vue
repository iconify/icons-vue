<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="gp_8x1bzb"><path class="yopdcqsuw"/><path class="pxqe3nblm"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:arrow-down-wide-narrow-sharp-duotone" /></template>
<style>
.gp_8x1bzb {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.pxqe3nblm {
  d: path("M6 5L6 18M1.7071 13.7071L6 18L10.2929 13.7071");
}

.yopdcqsuw {
  stroke-opacity: 0.4;
  d: path("M13 6L23 6M13 10L21 10M13 14L19 14M13 18L17 18");
}

</style>
