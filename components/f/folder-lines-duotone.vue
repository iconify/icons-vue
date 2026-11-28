<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="phbe2ybqe"/><path class="z18bwc1px"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:folder-lines-duotone" /></template>
<style>
.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.phbe2ybqe {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M2 7C2 4.7909 3.7909 3 6 3L8.6716 3C9.4672 3 10.2303 3.3161 10.7929 3.8787L12.1213 5.2071C12.3089 5.3946 12.5632 5.5 12.8284 5.5L18 5.5C20.2091 5.5 22 7.2909 22 9.5L22 17C22 19.2091 20.2091 21 18 21L6 21C3.7909 21 2 19.2091 2 17Z");
  stroke: none;
}

.z18bwc1px {
  d: path("M8 11L16 11M8 15L13 15");
}

</style>
