<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="ioj8z8i5q"/><path class="f_m71knqm"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:bot-droplet-duotone" /></template>
<style>
.f_m71knqm {
  d: path("M10 11.6028L10.4521 14.5685M13.9543 11L14.4064 13.9657");
}

.ioj8z8i5q {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M19.2 8.6C20.3684 10.1579 21 12.0527 21 14C21 18.9706 16.9706 23 12 23C7.0294 23 3 18.9706 3 14C3 12.0527 3.6316 10.1579 4.8 8.6L9.6 2.2C10.1666 1.4446 11.0557 1 12 1C12.9443 1 13.8334 1.4446 14.4 2.2L19.2 8.6Z");
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
