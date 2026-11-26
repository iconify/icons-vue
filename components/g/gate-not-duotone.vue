<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="u9ydjgo0u"/><path class="k4khy_8bl"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:gate-not-duotone" /></template>
<style>
.k4khy_8bl {
  d: path("M18 12C18 10.8954 18.8954 10 20 10C21.1046 10 22 10.8954 22 12C22 13.1046 21.1046 14 20 14C18.8954 14 18 13.1046 18 12ZM2 12L7 12");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.u9ydjgo0u {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M13.4712 7.7516L17.9712 10.2516C18.6062 10.6044 19 11.2736 19 12C19 12.7264 18.6062 13.3956 17.9713 13.7483L8.9712 18.7484C8.6741 18.9134 8.3397 19 8 19C6.8954 19 6 18.1046 6 17L6 7C6 5.8954 6.8954 5 8 5C8.3397 5 8.6741 5.0866 8.9712 5.2516Z");
  stroke: none;
}

</style>
