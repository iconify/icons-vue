<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="gp_8x1bzb"><path class="xd5vpds0d"/><path class="nw0f-gbpt"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:caret-left-sharp-fill" /></template>
<style>
.gp_8x1bzb {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.nw0f-gbpt {
  d: path("M6 12L18 19L18 5L6 12Z");
}

.xd5vpds0d {
  fill: currentColor;
  d: path("M6.2587 12.456L17.2159 18.9273C17.5635 19.1326 18 18.8787 18 18.4713L18 5.5287C18 5.1213 17.5635 4.8674 17.2159 5.0727L6.2587 11.544C5.9138 11.7477 5.9138 12.2523 6.2587 12.456Z");
  stroke: none;
}

</style>
