<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="w15dzk6ki"/><path class="wo0n5u8rd"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:hot-tub-two-tone" /></template>
<style>
.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.w15dzk6ki {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M3 10L21 10C21.5523 10 22 10.4477 22 11L22 15C22 17.7614 19.7614 20 17 20L7 20C4.2386 20 2 17.7614 2 15L2 11C2 10.4477 2.4477 10 3 10Z");
  stroke: none;
}

.wo0n5u8rd {
  d: path("M3 11L3 15C3 17.2091 4.7909 19 7 19L17 19C19.2091 19 21 17.2091 21 15L21 11M2 11L22 11M8 19L7 21M16 19L17 21M3 11L3 6C3 4.3431 4.3431 3 6 3C7.0463 3 8.0169 3.5451 8.5615 4.4384M7.5 5.5L10 3M15 3L15 3.1972C15 4.3727 14.6521 5.5219 14 6.5C13.8919 6.6622 13.7921 6.8291 13.7009 7M20 3L20 3.1972C20 4.3727 19.6521 5.5219 19 6.5C18.8919 6.6622 18.7921 6.8291 18.7009 7");
}

</style>
