<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="zag-a8bko"/><path class="x9x2jit3m"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:coffee-pot-fill" /></template>
<style>
.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.x9x2jit3m {
  d: path("M15 4L17 4C19.2091 4 21 5.7909 21 8L21 11");
}

.zag-a8bko {
  fill: currentColor;
  d: path("M4.675 9.0377L2.9611 5.9772C2.7939 5.6786 2.7061 5.3422 2.7061 5C2.7061 3.8954 3.6015 3 4.7061 3L15.2939 3C16.3985 3 17.2939 3.8954 17.2939 5C17.2939 5.3422 17.2061 5.6786 17.0389 5.9772L15.325 9.0377L17.3432 13.2851C17.3479 13.295 17.3525 13.305 17.3568 13.315L17.584 13.8367C17.8584 14.4666 18 15.1463 18 15.8333L18 16.4189C18.0001 18.949 15.949 21.0001 13.4189 21L6.5811 21C4.051 21.0001 1.9999 18.949 2 16.4189L2 15.8333C2 15.1462 2.1416 14.4666 2.416 13.8367L2.6432 13.315C2.6476 13.3049 2.6521 13.295 2.6568 13.2851L4.675 9.0377Z");
  stroke: none;
}

</style>
