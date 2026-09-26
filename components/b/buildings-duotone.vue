<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="nwglgkb1l"/><path class="lm_3feq5u"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:buildings-duotone" /></template>
<style>
.lm_3feq5u {
  d: path("M14 6L14 8M14 12L14 14M18 6L18 8M18 12L18 14M6 10L6 12M6 16L6 18M14 22L14 20C14 18.8954 14.8954 18 16 18C17.1046 18 18 18.8954 18 20L18 22");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.nwglgkb1l {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M3.5 5L9 5L9 4C9 2.3431 10.3431 1 12 1L20 1C21.6569 1 23 2.3431 23 4L23 20C23 21.6569 21.6569 23 20 23L3.5 23C2.1193 23 1 21.8807 1 20.5L1 7.5C1 6.1193 2.1193 5 3.5 5Z");
  stroke: none;
}

</style>
