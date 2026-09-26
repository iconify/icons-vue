<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="gp_8x1bzb"><path clip-rule="evenodd" class="lsbkd1bnn"/><path class="etugwackk"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:banknote-2-minus-sharp-fill" /></template>
<style>
.etugwackk {
  d: path("M22 13L22 2L2 2L2 16L13 16M18 2C18 3.3333 18.8 6 22 6M6 16C6 14.6667 5.2 12 2 12M6 2C6 3.3333 5.2 6 2 6M23 19L15 19");
}

.gp_8x1bzb {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.lsbkd1bnn {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M6 2L18 2C18 3.33333 18.8 6 22 6L22 13L13 13L13 16L6 16C6 14.6667 5.2 12 2 12L2 6C5.2 6 6 3.33333 6 2ZM15 9C15 7.3431 13.6569 6 12 6C10.3431 6 9 7.3431 9 9C9 10.6569 10.3431 12 12 12C13.6569 12 15 10.6569 15 9ZM13 9C13 9.5523 12.5523 10 12 10C11.4477 10 11 9.5523 11 9C11 8.4477 11.4477 8 12 8C12.5523 8 13 8.4477 13 9Z");
  stroke: none;
}

</style>
