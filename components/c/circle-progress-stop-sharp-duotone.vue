<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="gp_8x1bzb"><path class="t0_3emlbr"/><path class="by3trvvnz"/><path class="bkbniqb5o"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:circle-progress-stop-sharp-duotone" /></template>
<style>
.bkbniqb5o {
  fill: currentColor;
  d: path("M9 8L15 8C15.5523 8 16 8.4477 16 9L16 15C16 15.5523 15.5523 16 15 16L9 16C8.4477 16 8 15.5523 8 15L8 9C8 8.4477 8.4477 8 9 8Z");
  stroke: none;
}

.by3trvvnz {
  d: path("M13 22L12 22C6.4771 22 2 17.5229 2 12C2 6.4771 6.4771 2 12 2L13 2");
}

.gp_8x1bzb {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.t0_3emlbr {
  stroke-opacity: 0.4;
  d: path("M17.0688 3.3221L17.8778 3.9098C18.7268 4.5266 19.4734 5.2732 20.0902 6.1222L20.678 6.9312M21.7205 9.448L21.8769 10.4357C22.041 11.4721 22.041 12.5279 21.8769 13.5643L21.7205 14.552M20.678 17.0688L20.0902 17.8778C19.4734 18.7268 18.7268 19.4734 17.8778 20.0902L17.0688 20.678");
}

</style>
