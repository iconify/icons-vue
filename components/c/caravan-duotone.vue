<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="lc_3otsfp"/><path clip-rule="evenodd" class="fadr69bgk"/><path class="b_nbonb-s"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:caravan-duotone" /></template>
<style>
.b_nbonb-s {
  d: path("M10 18C10 19.1046 9.1046 20 8 20C6.8954 20 6 19.1046 6 18C6 16.8954 6.8954 16 8 16C9.1046 16 10 16.8954 10 18Z");
}

.fadr69bgk {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M3 7L4.5 7C5.8807 7 7 8.1193 7 9.5L7 10.5C7 11.8807 5.8807 13 4.5 13L3 13L3 7ZM9 13.1L9 9C9 7.8954 9.8954 7 11 7L14 7C15.1046 7 16 7.8954 16 9L16 17L12.9 17C12.4979 15.0365 10.9635 13.5021 9 13.1Z");
  stroke: none;
}

.lc_3otsfp {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M20 15L20 16C20 17.6569 18.6569 19 17 19L4 19C2.3431 19 1 17.6569 1 16L1 6C1 4.3431 2.3431 3 4 3L15 3C17.7614 3 20 5.2386 20 8L20 13L22 13C22.5523 13 23 13.4477 23 14C23 14.5523 22.5523 15 22 15L20 15Z");
  stroke: none;
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

</style>
