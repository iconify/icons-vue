<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="x6ma3nbxt"/><path class="h2-2dgnfu"/><path class="ae-e09b3w"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:compass-rose-outline-regular" /></template>
<style>
.ae-e09b3w {
  d: path("M3 12h18");
}

.h2-2dgnfu {
  d: path("M12 3v18");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.x6ma3nbxt {
  d: path("m12 3 9 9 -9 9 -9 -9Z");
}

</style>
