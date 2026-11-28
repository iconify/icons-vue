<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="x0wz5jbny"/><path class="t1-xpmbse"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:border-inside-duotone" /></template>
<style>
.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.t1-xpmbse {
  d: path("M10.5 3H13.5M21 10.5V13.5M13.5 21H10.5M3 13.5V10.5M12 3V21M3 12H21");
}

.x0wz5jbny {
  stroke-opacity: 0.4;
  d: path("M3 6C3 4.34315 4.34315 3 6 3M18 3C19.6569 3 21 4.34315 21 6M21 18C21 19.6569 19.6569 21 18 21M6 21C4.34315 21 3 19.6569 3 18");
}

</style>
