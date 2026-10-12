<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="vf16mbw1b"/><circle class="p_flhjbml"/><path class="z_us3kbag"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:image-plus" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.p_flhjbml {
  cx: 8.5px;
  cy: 9px;
  r: 1.75px;
}

.vf16mbw1b {
  d: path("M11.75 20.25h-6.5a2.5 2.5 0 0 1-2.5-2.5V6.25a2.5 2.5 0 0 1 2.5-2.5h13.5a2.5 2.5 0 0 1 2.5 2.5v5.5");
}

.z_us3kbag {
  d: path("m2.75 16.25l4.1-4.1a1.6 1.6 0 0 1 2.25 0l3.15 3.15m5.25-.55v5.5m-2.75-2.75h5.5");
}

</style>
