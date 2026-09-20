<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="x20zxc0rm"/><path class="ti3rw-2xs"/><path class="mg7aqnbsf"/><path class="rtofn9dtv"/><path class="b26q0zi5z"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:align-start-horizontal-duotone-bold" /></template>
<style>
.b26q0zi5z {
  d: path("M14 7h4v6h-4Z");
}

.mg7aqnbsf {
  d: path("M3 4h18");
}

.rtofn9dtv {
  d: path("M7 7h4v10H7Z");
}

.s0phu2bbs {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
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
