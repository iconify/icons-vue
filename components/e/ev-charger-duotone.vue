<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="fpb1ncb2s"/><path class="sur3qivno"/><path class="j4wc7bckm"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:ev-charger-duotone" /></template>
<style>
.fpb1ncb2s {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M14 23L2 23C1.4477 23 1 22.5523 1 22L1 5C1 2.7908 2.7908 1 5 1L11 1C13.2092 1 15 2.7908 15 5L15 21L22 21C22.5523 21 23 21.4477 23 22C23 22.5523 22.5523 23 22 23L14 23Z");
  stroke: none;
}

.j4wc7bckm {
  fill: currentColor;
  d: path("M18 5L22 5C22.5523 5 23 5.4477 23 6L23 8.5C23 9.8807 21.8807 11 20.5 11L19.5 11C18.1193 11 17 9.8807 17 8.5L17 6C17 5.4477 17.4477 5 18 5Z");
  stroke: none;
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.sur3qivno {
  d: path("M9 8L6 12L10 12L7 16M14 17L18 17C19.1046 17 20 16.1046 20 15L20 10M22 6L22 4M18 6L18 4");
}

</style>
