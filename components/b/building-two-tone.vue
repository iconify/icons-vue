<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="b84h-bczg"/><path class="n53fgpbbm"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:building-two-tone" /></template>
<style>
.b84h-bczg {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M7 1H17C19.20914 1 21 2.79086 21 5V19C21 21.20914 19.20914 23 17 23H7C4.79086 23 3 21.20914 3 19V5C3 2.79086 4.79086 1 7 1Z");
  stroke: none;
}

.n53fgpbbm {
  d: path("M7 2H17C18.65685 2 20 3.34315 20 5V19C20 20.65685 18.65685 22 17 22H7C5.34315 22 4 20.65685 4 19V5C4 3.34315 5.34315 2 7 2ZM10 22V20C10 18.89543 10.89543 18 12 18C13.10457 18 14 18.89543 14 20V22M9 6V8M15 6V8M9 12V14M15 12V14");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

</style>
