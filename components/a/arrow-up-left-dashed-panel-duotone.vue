<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="vxfx8lbfs"/><path class="afn_a9b2v"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:arrow-up-left-dashed-panel-duotone" /></template>
<style>
.afn_a9b2v {
  d: path("M12.5 12.5L3.5 3.5M3 12.5L3 3.5C3 3.2239 3.2239 3 3.5 3L12.5 3");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.vxfx8lbfs {
  stroke-opacity: 0.4;
  d: path("M10.5 21L13.5 21M21 13.5L21 10.5M3 17L3 18C3 19.6569 4.3431 21 6 21M18 21C19.6569 21 21 19.6569 21 18M17 3L18 3C19.6569 3 21 4.3431 21 6");
}

</style>
