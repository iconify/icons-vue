<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="gp_8x1bzb"><path class="gx0xjxlxa"/><path class="bfgkgvs1u"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:audio-lines-sharp-two-tone" /></template>
<style>
.bfgkgvs1u {
  d: path("M4 9L4 15M12 2L12 22M20 9L20 15");
}

.gp_8x1bzb {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.gx0xjxlxa {
  stroke-opacity: 0.4;
  d: path("M8 5L8 19M16 6L16 18");
}

</style>
