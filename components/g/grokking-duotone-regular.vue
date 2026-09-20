<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="gb7yzvvzz"/><path class="ufh76fbbg"/><path class="qe97cg-lx"/><path class="qj99nibfx"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:grokking-duotone-regular" /></template>
<style>
.gb7yzvvzz {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M3 3v18h18");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.qe97cg-lx {
  d: path("M3 3v18h18");
}

.qj99nibfx {
  d: path("M6 18h8l4 -4V6");
}

.ufh76fbbg {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M6 18h8l4 -4V6");
  opacity: var(--svg-opacity--0-2, 0.2);
}

</style>
