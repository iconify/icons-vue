<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="t8drw368i"/><path class="pfvayjbbu"/><path class="cxhoxcc8c"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:accessibility-duotone" /></template>
<style>
.cxhoxcc8c {
  fill: currentColor;
  d: path("M13.5 6.5C13.5 7.3284 12.8284 8 12 8C11.1716 8 10.5 7.3284 10.5 6.5C10.5 5.6716 11.1716 5 12 5C12.8284 5 13.5 5.6716 13.5 6.5Z");
  stroke: none;
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.pfvayjbbu {
  d: path("M8 11L16 11M12 11L12 13M10 17L12 13L14 17");
}

.t8drw368i {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M23 12C23 18.0751 18.0751 23 12 23C5.9249 23 1 18.0751 1 12C1 5.9249 5.9249 1 12 1C18.0751 1 23 5.9249 23 12Z");
  stroke: none;
}

</style>
