<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="y9tr6bcfx"><path class="fq81x4j2j"/><path class="po156s2av"/><path class="sqy-g19gq"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:ev-plug" /></template>
<style>
.fq81x4j2j {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M6.5 3.5h11a7.25 7.25 0 1 1-11 0");
}

.po156s2av {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M9 7.75h.01m2.99-.5h.01m2.99.5h.01m-4.76 3.5h.01m3.49 0h.01");
}

.sqy-g19gq {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M12 16.5v1.75a3 3 0 0 0 3 3h6.25");
}

.y9tr6bcfx {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>
