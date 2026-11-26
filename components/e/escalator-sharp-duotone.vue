<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="gp_8x1bzb"><path class="g23h9qw8w"/><path class="x09dt0bpg"/><path class="y1y3j_bom"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:escalator-sharp-duotone" /></template>
<style>
.g23h9qw8w {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M10.0502 10.2929L14.0503 6.2929C14.2378 6.1054 14.4922 6 14.7574 6L19 6C21.2092 6 23 7.7908 23 10C23 12.2092 21.2092 14 19 14L17.6569 14L9.9497 21.7071C9.7622 21.8946 9.5078 22 9.2426 22L5 22C2.7908 22 1 20.2092 1 18C1 15.7908 2.7908 14 5 14L6.3431 14Z");
  stroke: none;
}

.gp_8x1bzb {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.x09dt0bpg {
  d: path("M4 7L4 8L4 11L4 12");
}

.y1y3j_bom {
  fill: currentColor;
  d: path("M5.5 3.5C5.5 4.3284 4.8284 5 4 5C3.1716 5 2.5 4.3284 2.5 3.5C2.5 2.6716 3.1716 2 4 2C4.8284 2 5.5 2.6716 5.5 3.5Z");
  stroke: none;
}

</style>
