<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="z9ftpgb_y"/><circle class="ivl5k1bso"/><path class="jpa2tta9t"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:halo-ring" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.ivl5k1bso {
  cx: 12px;
  cy: 11px;
  r: 2.75px;
}

.jpa2tta9t {
  d: path("M4.5 21.25c0-3 3.25-5 7.5-5s7.5 2 7.5 5Z");
}

.z9ftpgb_y {
  d: path("M12 2.75c3.6 0 6.5.67 6.5 1.5s-2.9 1.5-6.5 1.5s-6.5-.67-6.5-1.5s2.9-1.5 6.5-1.5");
}

</style>
