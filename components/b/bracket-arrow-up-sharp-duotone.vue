<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="gp_8x1bzb"><path class="u0nfmxh_m"/><path class="b9opflstk"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:bracket-arrow-up-sharp-duotone" /></template>
<style>
.b9opflstk {
  d: path("M12 2.2414L12 13.8907M17.796 8.1438L12 2L6.204 8.1438");
}

.gp_8x1bzb {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.u0nfmxh_m {
  stroke-opacity: 0.4;
  d: path("M20 11.8907L20 22L4 22L4 11.8907");
}

</style>
