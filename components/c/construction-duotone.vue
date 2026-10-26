<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="rzxra0m-i"/><path clip-rule="evenodd" class="z_3-myb6x"/><path class="sg3s0jkvp"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:construction-duotone" /></template>
<style>
.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.rzxra0m-i {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M4 3L20 3C21.6569 3 23 4.3431 23 6L23 9C23 10.6569 21.6569 12 20 12L4 12C2.3431 12 1 10.6569 1 9L1 6C1 4.3431 2.3431 3 4 3Z");
  stroke: none;
}

.sg3s0jkvp {
  d: path("M6 11L6 20M18 11L18 20M4 20L8 20M16 20L20 20");
}

.z_3-myb6x {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M3.1952 11.8906L12.0858 3L14.9142 3L5.9142 12L4 12C3.728 12.0002 3.4573 11.9633 3.1952 11.8906ZM9.0858 12L18.0858 3L20 3C20.272 2.9998 20.5427 3.0367 20.8048 3.1094L11.9142 12L9.0858 12Z");
  stroke: none;
}

</style>
