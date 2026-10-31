<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="gp_8x1bzb"><path class="udwo0bb1i"/><path class="b4bm88plz"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:barn-sharp-two-tone" /></template>
<style>
.b4bm88plz {
  d: path("M2 22L2 10L6 5L12 2L18 5L22 10L22 22ZM8 22L8 16L16 16L16 22M16 22L8 16M10 8L14 8L14 12L10 12Z");
}

.gp_8x1bzb {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.udwo0bb1i {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M1 22L1 10C1 9.7729 1.0773 9.5526 1.2191 9.3753L5.2191 4.3753C5.3095 4.2623 5.4234 4.1703 5.5528 4.1056L11.5528 1.1056C11.6916 1.0361 11.8448 1 12 1C12.1552 1 12.3084 1.0361 12.4472 1.1056L18.4472 4.1056C18.5766 4.1703 18.6905 4.2623 18.7809 4.3753L22.7809 9.3753C22.9227 9.5526 23 9.7729 23 10L23 22C23 22.5523 22.5523 23 22 23L2 23C1.4477 23 1 22.5523 1 22Z");
  stroke: none;
}

</style>
