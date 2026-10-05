<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="dw2a6bc1h"/><path class="l27kgwbzk"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:house-cast-fill" /></template>
<style>
.dw2a6bc1h {
  d: path("M2 17C4.2091 17 6 18.7909 6 21M2 13C6.4183 13 10 16.5817 10 21M3.9852 9.1654L10.7072 3.4703C11.4532 2.8383 12.5468 2.8383 13.2928 3.4703L22 10.8473M20 9.1528L20 19C20 20.1046 19.1046 21 18 21L14 21");
}

.l27kgwbzk {
  fill: currentColor;
  d: path("M3 21C3 21.5523 2.5523 22 2 22C1.4477 22 1 21.5523 1 21C1 20.4477 1.4477 20 2 20C2.5523 20 3 20.4477 3 21Z");
  stroke: none;
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

</style>
