<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="gp_8x1bzb"><path class="hunpuscot"/><path class="qhiywlzct"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:bookmark-x-sharp-two-tone" /></template>
<style>
.gp_8x1bzb {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.hunpuscot {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M4 1L11 1L11 11L21 11L21 22C21 22.5523 20.5523 23 20 23C19.8593 23 19.7202 22.9703 19.5918 22.9129L12 19.5177L4.4082 22.9129C4.2798 22.9703 4.1407 23 4 23C3.4477 23 3 22.5523 3 22L3 2C3 1.4477 3.4477 1 4 1Z");
  stroke: none;
}

.qhiywlzct {
  d: path("M20 11L20 22L12 18.4223L4 22L4 2L11 2M13.7071 1.7071L20.2929 8.2929M20.2929 1.7071L13.7071 8.2929");
}

</style>
