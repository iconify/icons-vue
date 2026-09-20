<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="x20zxc0rm"/><path class="qfaesy8qk"/><path class="jkuojibnm"/><path class="rtofn9dtv"/><path class="qc4g9_58r"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:align-end-horizontal-duotone-regular" /></template>
<style>
.jkuojibnm {
  d: path("M3 20h18");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.qc4g9_58r {
  d: path("M14 11h4v6h-4Z");
}

.qfaesy8qk {
  fill: currentColor;
  d: path("M14 11h4v6h-4Z");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

.rtofn9dtv {
  d: path("M7 7h4v10H7Z");
}

.x20zxc0rm {
  fill: currentColor;
  d: path("M7 7h4v10H7Z");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

</style>
