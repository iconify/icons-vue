<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="walbv2b5n"/><path class="wd09ntbpx"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:heading-6-duotone" /></template>
<style>
.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.walbv2b5n {
  stroke-opacity: 0.4;
  d: path("M2 4V20M11 4V20M2 12H11");
}

.wd09ntbpx {
  d: path("M17 18C17 16.8954 17.8954 16 19 16C20.1046 16 21 16.8954 21 18C21 19.1046 20.1046 20 19 20C17.8954 20 17 19.1046 17 18ZM17 18C17 15.5811 18.7178 13.4633 21 13");
}

</style>
