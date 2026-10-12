<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="y9tr6bcfx"><path class="vvuoc9b3w"/><path class="to8m3ibcr"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:blob" /></template>
<style>
.to8m3ibcr {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M12 12h.01");
}

.vvuoc9b3w {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M12 3c3-.25 4.5 2 6.75 2.5s3 3.5 1.75 6s-1 4.75-2.75 6.75s-5 1.5-7.25 2.25S4.75 20 4.25 17s1.25-4-.5-6.5S8.75 3.25 12 3");
}

.y9tr6bcfx {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>
