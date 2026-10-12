<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="x_7j9ab6j"/><path class="wlhtl2bmc"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:input-cursor-fill" /></template>
<style>
.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.wlhtl2bmc {
  fill: currentColor;
  d: path("M16.8199 17.1405L15.0585 11.608C15.0201 11.4871 15.0005 11.361 15.0005 11.2342C15.0005 10.5527 15.553 10.0002 16.2345 10.0002C16.3671 10.0002 16.4989 10.0216 16.6248 10.0636L22.1558 11.9051C22.6599 12.0727 23 12.5442 23 13.0754C23 13.5742 22.6996 14.0238 22.2389 14.2148L20.1495 15.0816L19.1136 17.2904C18.9101 17.7235 18.4747 18 17.9962 18C17.4589 18 16.9832 17.6524 16.8199 17.1405Z");
  stroke: none;
}

.x_7j9ab6j {
  d: path("M20 7L4 7C2.8954 7 2 7.8954 2 9L2 15C2 16.1046 2.8954 17 4 17L12 17M6 11L6 13");
}

</style>
