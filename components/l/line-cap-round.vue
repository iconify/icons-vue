<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="y9tr6bcfx"><path class="p0pxc78zf"/><path class="wb2vpv6rb"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:line-cap-round" /></template>
<style>
.p0pxc78zf {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.75 7.25h11.5a4.75 4.75 0 0 1 0 9.5H2.75m0-4.75h11.5");
}

.wb2vpv6rb {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M14.25 12h.01");
}

.y9tr6bcfx {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>
