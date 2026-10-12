<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="y9tr6bcfx"><path class="mol-t4-is"/><path class="meoxs6j0n"/><path class="j7iy7ccxz"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:acne-spot" /></template>
<style>
.j7iy7ccxz {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M9.83 10.25L8.54 9.5m5.63.75l1.29-.75");
}

.meoxs6j0n {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M12 11.5h.01");
}

.mol-t4-is {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.75 17.75c4 0 6-.25 7-1.75s3.5-1.5 4.5 0s3 1.75 7 1.75");
}

.y9tr6bcfx {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>
