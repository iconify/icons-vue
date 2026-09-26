<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="qe9ascb5k"/><path class="rj2y4vkzd"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:airpods-open" /></template>
<style>
.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.qe9ascb5k {
  d: path("M3 9L21 9C21.5523 9 22 9.4477 22 10L22 16C22 18.7614 19.7614 21 17 21L7 21C4.2386 21 2 18.7614 2 16L2 10C2 9.4477 2.4477 9 3 9ZM3.7961 9C1.9535 6.6308 3.461 3.4056 6.7609 3L17.2391 3C20.539 3.4056 22.0465 6.6308 20.2039 9M8 9C8 9.5523 8.4477 10 9 10L15 10C15.5523 10 16 9.5523 16 9");
}

.rj2y4vkzd {
  fill: currentColor;
  d: path("M13 14C13 14.5523 12.5523 15 12 15C11.4477 15 11 14.5523 11 14C11 13.4477 11.4477 13 12 13C12.5523 13 13 13.4477 13 14Z");
  stroke: none;
}

</style>
