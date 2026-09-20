<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="ht74g2xqg"/><path class="ph1z-dbce"/><path class="bbxz-u7vo"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:hearing-aid-outline-regular" /></template>
<style>
.bbxz-u7vo {
  d: path("M16 6a6 6 0 0 1 0 12");
}

.ht74g2xqg {
  d: path("M6 20A6 6 0 0 1 6 8a4 4 0 0 1 6 8");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.ph1z-dbce {
  d: path("M16 9a3 3 0 0 1 0 6");
}

</style>
