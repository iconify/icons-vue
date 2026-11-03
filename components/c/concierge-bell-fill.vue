<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path clip-rule="evenodd" class="m4am4ab_s"/><path class="fyu52ibxo"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:concierge-bell-fill" /></template>
<style>
.fyu52ibxo {
  d: path("M12 7L12 3M9 3L15 3");
}

.m4am4ab_s {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M4.148 10.599C5.7404 7.7579 8.7433 5.9986 12.0002 5.9986C15.2571 5.9986 18.26 7.7579 19.8524 10.599C19.9078 10.7255 19.9364 10.862 19.9364 11.0001C19.9364 11.5524 19.4886 12.0001 18.9363 12L5.064 12C4.5117 12.0001 4.064 11.5525 4.064 11.0002C4.064 10.8621 4.0926 10.7255 4.148 10.599ZM4 14L20 14C21.6569 14 23 15.3431 23 17L23 19C23 20.6569 21.6569 22 20 22L4 22C2.3431 22 1 20.6569 1 19L1 17C1 15.3431 2.3431 14 4 14Z");
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
