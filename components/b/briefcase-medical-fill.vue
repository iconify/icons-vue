<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path clip-rule="evenodd" class="m1ur1bvwz"/><path class="y5ehe7ela"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:briefcase-medical-fill" /></template>
<style>
.m1ur1bvwz {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M5 5.5L19 5.5C21.2091 5.5 23 7.2909 23 9.5L23 18C23 20.2091 21.2091 22 19 22L5 22C2.7909 22 1 20.2091 1 18L1 9.5C1 7.2909 2.7909 5.5 5 5.5ZM11 10C10.7239 10 10.5 10.2239 10.5 10.5L10.5 12C10.5 12.2761 10.2761 12.5 10 12.5L8.5 12.5C8.2239 12.5 8 12.7239 8 13L8 15C8 15.2761 8.2239 15.5 8.5 15.5L10 15.5C10.2761 15.5 10.5 15.7239 10.5 16L10.5 17.5C10.5 17.7761 10.7239 18 11 18L13 18C13.2761 18 13.5 17.7761 13.5 17.5L13.5 16C13.5 15.7239 13.7239 15.5 14 15.5L15.5 15.5C15.7761 15.5 16 15.2761 16 15L16 13C16 12.7239 15.7761 12.5 15.5 12.5L14 12.5C13.7239 12.5 13.5 12.2761 13.5 12L13.5 10.5C13.5 10.2239 13.2761 10 13 10L11 10Z");
  stroke: none;
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.y5ehe7ela {
  d: path("M8.25 6.5L8.25 6C8.25 4.3431 9.5931 3 11.25 3L12.75 3C14.4069 3 15.75 4.3431 15.75 6L15.75 6.5");
}

</style>
