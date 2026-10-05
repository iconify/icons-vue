<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="gp_8x1bzb"><path class="mg5_1mbjp"/><path class="m--g3acqf"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:arrow-up-down-2-sharp-duotone" /></template>
<style>
.gp_8x1bzb {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.m--g3acqf {
  d: path("M7 23L7 22L7 11.7396L7 11.0856M12.2939 16.1938L12 15.8947L7 10.8066L2 15.8947L1.7061 16.1938");
}

.mg5_1mbjp {
  stroke-opacity: 0.4;
  d: path("M17 1L17 2L17 12.2604L17 12.9144M11.7061 7.8062L12 8.1053L17 13.1934L22 8.1053L22.2939 7.8062");
}

</style>
