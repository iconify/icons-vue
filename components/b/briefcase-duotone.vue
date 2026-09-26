<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="g7fhqy1lz"/><path class="a4m4b3elc"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:briefcase-duotone" /></template>
<style>
.a4m4b3elc {
  d: path("M8.25 6C8.25 4.3431 9.5931 3 11.25 3L12.75 3C14.4069 3 15.75 4.3431 15.75 6M2 10.5C6 12.75 18 12.75 22 10.5M9.5 12.1132L9.5 13.5C9.5 14.6046 10.3954 15.5 11.5 15.5L12.5 15.5C13.6046 15.5 14.5 14.6046 14.5 13.5L14.5 12.1132");
}

.g7fhqy1lz {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M5 5.5L19 5.5C21.2091 5.5 23 7.2909 23 9.5L23 18C23 20.2091 21.2091 22 19 22L5 22C2.7909 22 1 20.2091 1 18L1 9.5C1 7.2909 2.7909 5.5 5 5.5Z");
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
