<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="niggb1byh"/><path class="gdju1xbel"/><path class="wzhctub5z"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:magnetic-field-outline-regular" /></template>
<style>
.gdju1xbel {
  d: path("M3 13c0 -9 18 -9 18 0");
}

.niggb1byh {
  d: path("M8 10h8v4H8Z");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.wzhctub5z {
  d: path("M3 11c0 9 18 9 18 0");
}

</style>
