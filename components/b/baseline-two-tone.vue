<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="we9hhjpft"/><path class="p9e_gacjh"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:baseline-two-tone" /></template>
<style>
.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.p9e_gacjh {
  d: path("M3 21H21");
}

.we9hhjpft {
  stroke-opacity: 0.4;
  d: path("M6 17L11.065 3.6454C11.3914 2.7849 12.6086 2.7849 12.935 3.6454L18 17M7.5171 13H16.4829");
}

</style>
