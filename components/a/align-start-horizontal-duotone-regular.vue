<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="x20zxc0rm"/><path class="ti3rw-2xs"/><path class="mg7aqnbsf"/><path class="rtofn9dtv"/><path class="b26q0zi5z"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:align-start-horizontal-duotone-regular" /></template>
<style>
.b26q0zi5z {
  d: path("M14 7h4v6h-4Z");
}

.mg7aqnbsf {
  d: path("M3 4h18");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.rtofn9dtv {
  d: path("M7 7h4v10H7Z");
}

.ti3rw-2xs {
  fill: currentColor;
  d: path("M14 7h4v6h-4Z");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

.x20zxc0rm {
  fill: currentColor;
  d: path("M7 7h4v10H7Z");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

</style>
