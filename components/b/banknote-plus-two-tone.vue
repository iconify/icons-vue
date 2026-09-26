<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="dwufu6b3h"/><path class="p0wspmbie"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:banknote-plus-two-tone" /></template>
<style>
.dwufu6b3h {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M4 1L20 1C21.6569 1 23 2.3431 23 4L23 12C23 12.5523 22.5523 13 22 13L16 13C14.3431 13 13 14.3431 13 16C13 16.5523 12.5523 17 12 17L4 17C2.3431 17 1 15.6569 1 14L1 4C1 2.3431 2.3431 1 4 1Z");
  stroke: none;
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.p0wspmbie {
  d: path("M22 12L22 4C22 2.8954 21.1046 2 20 2L4 2C2.8954 2 2 2.8954 2 4L2 14C2 15.1046 2.8954 16 4 16L12 16M14 9C14 10.1046 13.1046 11 12 11C10.8954 11 10 10.1046 10 9C10 7.8954 10.8954 7 12 7C13.1046 7 14 7.8954 14 9ZM17 6L18 6M7 12L6 12M19 16V22M22 19H16");
}

</style>
