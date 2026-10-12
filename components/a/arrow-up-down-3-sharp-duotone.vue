<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="gp_8x1bzb"><path class="w-11rtbnc"/><path class="r9qqk__tf"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:arrow-up-down-3-sharp-duotone" /></template>
<style>
.gp_8x1bzb {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.r9qqk__tf {
  d: path("M7 14L7 13L7 2.7396L7 2.0856M12.3005 7.1888L12 6.8947L7 2L2 6.8947L1.6995 7.1888");
}

.w-11rtbnc {
  stroke-opacity: 0.4;
  d: path("M17 10L17 11L17 21.2604L17 21.9144M11.6995 16.8112L12 17.1053L17 22L22 17.1053L22.3005 16.8112");
}

</style>
