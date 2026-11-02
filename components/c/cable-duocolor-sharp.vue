<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="rmzm0rtfm"/><path class="wta12jbge"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:cable-duocolor-sharp" /></template>
<style>
.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.rmzm0rtfm {
  stroke-opacity: 0.4;
  d: path("M7 9v3h10v3");
}

.wta12jbge {
  d: path("M3 5h8v4H3Zm10 10h8v4h-8ZM5 3v2m4-2v2m6 14v2m4-2v2");
}

</style>
