<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="makatac8t"/><path class="fe1sg20rn"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:flip-2-horizontal-fill" /></template>
<style>
.fe1sg20rn {
  d: path("M12 3L12 21M16 3L18 3C19.6569 3 21 4.3431 21 6M21 10.5L21 13.5M21 18C21 19.6569 19.6569 21 18 21L16 21");
}

.makatac8t {
  fill: currentColor;
  d: path("M2 6C2 3.7909 3.7909 2 6 2L8 2C8.5523 2 9 2.4477 9 3L9 21C9 21.5523 8.5523 22 8 22L6 22C3.7909 22 2 20.2091 2 18L2 6Z");
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
