<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path clip-rule="evenodd" class="z70g92czm"/><path class="c2mfu0bzz"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:gate-buffer-fill" /></template>
<style>
.c2mfu0bzz {
  d: path("M2 12L7 12M18 12L22 12");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.z70g92czm {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M13.4712 7.7516L17.9712 10.2516C18.6062 10.6044 19 11.2736 19 12C19 12.7264 18.6062 13.3956 17.9713 13.7483L8.9712 18.7484C8.6741 18.9134 8.3397 19 8 19C6.8954 19 6 18.1046 6 17L6 7C6 5.8954 6.8954 5 8 5C8.3397 5 8.6741 5.0866 8.9712 5.2516Z");
  stroke: none;
}

</style>
