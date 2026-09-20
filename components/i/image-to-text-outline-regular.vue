<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="o72p0hsyz"/><path class="wk-andm0z"/><path class="q60rll86p"/><path class="iv697recx"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:image-to-text-outline-regular" /></template>
<style>
.iv697recx {
  d: path("M7 16.5h6");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.o72p0hsyz {
  d: path("M14 4h4a3 3 0 0 1 3 3v10a3 3 0 0 1 -3 3H6a3 3 0 0 1 -3 -3V7a3 3 0 0 1 3 -3h4");
}

.q60rll86p {
  d: path("M7 13.5h10");
}

.wk-andm0z {
  d: path("m6 10 4 -4 4 4");
}

</style>
