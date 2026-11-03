<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="b6ka0h2iu"/><path class="py9sccrek"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:hot-tub-fill" /></template>
<style>
.b6ka0h2iu {
  fill: currentColor;
  d: path("M22 12.0001L22 15C22 17.7614 19.7614 20 17 20L7 20C4.2386 20 2 17.7614 2 15L2 12.0001C1.4477 12.0001 1 11.5523 1 11.0001C1 10.4478 1.4477 10.0001 2 10.0001L2.988 10.0001C2.992 10 2.996 10 3 10L21 10C21.004 10 21.008 10 21.012 10.0001L22 10.0001C22.5523 10.0001 23 10.4478 23 11.0001C23 11.5524 22.5523 12.0001 22 12.0001Z");
  stroke: none;
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.py9sccrek {
  d: path("M3 11L3 6C3 4.3431 4.3431 3 6 3C7.0463 3 8.0169 3.5451 8.5615 4.4384M7.5 5.5L10 3M8 19L7 21M16 19L17 21M15 3L15 3.1972C15 4.3727 14.6521 5.5219 14 6.5C13.8919 6.6622 13.7921 6.8291 13.7009 7M20 3L20 3.1972C20 4.3727 19.6521 5.5219 19 6.5C18.8919 6.6622 18.7921 6.8291 18.7009 7");
}

</style>
