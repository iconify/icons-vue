<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="y_mkwyfwm"/><path class="vxdmqy5yn"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:bot-off" /></template>
<style>
.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.vxdmqy5yn {
  fill: currentColor;
  d: path("M13.5 3.5C13.5 4.3284 12.8284 5 12 5C11.1716 5 10.5 4.3284 10.5 3.5C10.5 2.6716 11.1716 2 12 2C12.8284 2 13.5 2.6716 13.5 3.5ZM10 13C10 13.5523 9.5523 14 9 14C8.4477 14 8 13.5523 8 13C8 12.4477 8.4477 12 9 12C9.5523 12 10 12.4477 10 13Z");
  stroke: none;
}

.y_mkwyfwm {
  d: path("M19.5616 19.5616C19.017 20.4549 18.0463 21 17 21L7 21C5.3431 21 4 19.6569 4 18L4 11C4 9.3431 5.3431 8 7 8L8 8M22 14.5L20 14.5L20 11C20 9.3431 18.6569 8 17 8L12 8L12 3.5M2 14.5L4 14.5M9 17L13 17M2 2L22 22");
}

</style>
