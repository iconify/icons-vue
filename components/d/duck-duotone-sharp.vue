<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="iralotb8s"/><path class="b7m-mtb1v"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:duck-duotone-sharp" /></template>
<style>
.b7m-mtb1v {
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M7 9c-1.5.5-3 1.5-3 3c0 2.5 2 4 5 4h5c5 0 7-4 7-8c-3.5 2-7 2-9 1c0-.5 1-1.5 1-3c0-1.7-1.3-3-3-3S7 4.3 7 6v1m3-1h.01M3 20c1.5 0 1.5 1 3 1s1.5-1 3-1s1.5 1 3 1s1.5-1 3-1s1.5 1 3 1s1.5-1 3-1M7 7L3 8l4 1");
}

.ft5dv1b6b {
  fill: none;
}

.iralotb8s {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-2, 0.2);
  d: path("M13.335 8.436c1.544.41 3.259.22 4.766-.25a12 12 0 0 0 2.403-1.054A1 1 0 0 1 22 8a11.8 11.8 0 0 1-.428 3.21c-.294 1.036-.75 2.027-1.397 2.89c-1.5 1.999-3.711 2.9-6.175 2.9H9c-1.492 0-3.048-.338-4.243-1.276C3.59 14.806 3 13.475 3 12c0-.522.127-1.036.372-1.496c.231-.439.555-.822.926-1.149L2.757 8.97a1 1 0 0 1 0-1.94L6 6.219V6a4.03 4.03 0 0 1 1.155-2.845A4.03 4.03 0 0 1 10 2c2.248 0 4 1.752 4 4c0 .892-.268 1.656-.665 2.436");
}

</style>
