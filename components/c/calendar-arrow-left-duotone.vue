<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="bp-w5nx6c"/><path class="zp4-55bre"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:calendar-arrow-left-duotone" /></template>
<style>
.bp-w5nx6c {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M6 4H18C20.2091 4 22 5.79086 22 8V11C22 11.5523 21.5523 12 21 12H15C13.3431 12 12 13.3431 12 15V21C12 21.5523 11.5523 22 11 22H6C3.79086 22 2 20.2091 2 18V8C2 5.79086 3.79086 4 6 4Z");
  stroke: none;
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.zp4-55bre {
  d: path("M7 11L17 11M8 3L8 7M16 3L16 7M21 18L15 18M18 15L15 18L18 21");
}

</style>
