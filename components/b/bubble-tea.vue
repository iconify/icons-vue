<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="y9tr6bcfx"><path class="l4ptkjwme"/><path class="od_c_acvu"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:bubble-tea" /></template>
<style>
.l4ptkjwme {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M4.75 7.25h14.5l-1.5 12.5a1.75 1.75 0 0 1-1.75 1.5H8a1.75 1.75 0 0 1-1.75-1.5Zm8.75 0l2-4.5H18");
}

.od_c_acvu {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M9.75 18h.01m4.49 0h.01M12 14.5h.01");
}

.y9tr6bcfx {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>
