<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="y9tr6bcfx"><path class="y5gl65dko"/><path class="qz-djccyv"/><path class="hhx-69jmu"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:city-skyline" /></template>
<style>
.hhx-69jmu {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M13.5 4.5V2.75");
}

.qz-djccyv {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M8.9 11.5h.01m4.59-1h.01M13.5 14h.01m5.09 1.5h.01");
}

.y5gl65dko {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.75 20.85V13.4q0-.4.28-.68l1.44-1.44q.28-.28.56 0l1.44 1.44q.28.28.28-.12V8.4q0-.4.4-.4h3.45q.4 0 .4-.37q0-.38.4-.38h.2q.4 0 .4-.4V4.9q0-.4.4-.4h2.2q.4 0 .4.4v1.95q0 .4.4.4h.2q.4 0 .4.4v2.2q0 .4.37.54l4.51 1.72q.37.14.37.54v8.2q0 .4-.4.4H3.15q-.4 0-.4-.4m4-7.85v8.25M11 8v13.25m5-11v11");
}

.y9tr6bcfx {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>
