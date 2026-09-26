<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="vxfx8lbfs"/><path class="em-cwqg8e"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:arrow-in-down-right-dashed-panel-duotone" /></template>
<style>
.em-cwqg8e {
  d: path("M3 12.5L12 12.5C12.2761 12.5 12.5 12.2761 12.5 12L12.5 3M3 3L12 12");
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
