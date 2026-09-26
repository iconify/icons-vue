<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="cwab05iss"/><path class="xw9tycbcv"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:expand-dashed-down-left-duotone" /></template>
<style>
.cwab05iss {
  d: path("M13 6L3 6M6 3L3 6L6 9M18 11L18 21M15 18L18 21L21 18");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.xw9tycbcv {
  stroke-opacity: 0.4;
  d: path("M11 21L9.6667 21M5.6667 21C4.1939 21 3 19.8061 3 18.3333M3 14.3333L3 13");
}

</style>
