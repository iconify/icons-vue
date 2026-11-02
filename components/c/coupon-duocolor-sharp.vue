<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="fm0tjs-pa"/><path class="mbp5v3bfn"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:coupon-duocolor-sharp" /></template>
<style>
.fm0tjs-pa {
  stroke-opacity: 0.4;
  d: path("m14 10l-4 4M9 9h.01M15 15h.01");
}

.mbp5v3bfn {
  d: path("M21 9V6H3v3a3 3 0 0 1 0 6v3h18v-3a3 3 0 0 1 0-6");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

</style>
