<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path clip-rule="evenodd" class="fvs3tjb6p"/><path class="t1jdijb8m"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:luggage-fill" /></template>
<style>
.fvs3tjb6p {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M7 5L17 5C18.6569 5 20 6.3431 20 8L20 18C20 19.6569 18.6569 21 17 21L7 21C5.3431 21 4 19.6569 4 18L4 8C4 6.3431 5.3431 5 7 5ZM7 10C6.4477 10 6 10.4477 6 11C6 11.5523 6.4477 12 7 12L17 12C17.5523 12 18 11.5523 18 11C18 10.4477 17.5523 10 17 10L7 10Z");
  stroke: none;
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.t1jdijb8m {
  d: path("M8 6L8.6213 3.5149C8.8439 2.6246 9.6438 2 10.5616 2L13.4384 2C14.3562 2 15.1561 2.6246 15.3787 3.5149L16 6M7 20L7 22M17 20L17 22");
}

</style>
