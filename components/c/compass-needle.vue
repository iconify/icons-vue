<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="y9tr6bcfx"><path class="altcm-sza"/><path class="to8m3ibcr"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:compass-needle" /></template>
<style>
.altcm-sza {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m19.67 4.67l-4.59 9.41q-.33.67-.86.14L9.78 9.78q-.53-.53.14-.86l9.41-4.59q.67-.33.34.34M9.78 9.78l4.44 4.44q.53.53-.14.86l-9.41 4.59q-.67.33-.34-.34l4.59-9.41q.33-.67.86-.14");
}

.to8m3ibcr {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M12 12h.01");
}

.y9tr6bcfx {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>
