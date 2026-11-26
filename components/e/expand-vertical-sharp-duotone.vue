<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="gp_8x1bzb"><path class="e1yfpbcax"/><path class="v_7onzvxh"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:expand-vertical-sharp-duotone" /></template>
<style>
.e1yfpbcax {
  stroke-opacity: 0.4;
  d: path("M4 2L20 2M4 22L20 22");
}

.gp_8x1bzb {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.v_7onzvxh {
  d: path("M12 6L12 18M8.7071 9.2929L12 6L15.2929 9.2929M8.7071 14.7071L12 18L15.2929 14.7071");
}

</style>
