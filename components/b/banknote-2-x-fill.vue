<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path clip-rule="evenodd" class="g-015mbzc"/><path class="knxfuxbru"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:banknote-2-x-fill" /></template>
<style>
.g-015mbzc {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M6 2L18 2C18 3.33333 18.8 6 22 6L22 13L16 13C14.3431 13 13 14.3431 13 16L6 16C6 14.6667 5.2 12 2 12L2 6C5.2 6 6 3.33333 6 2ZM15 9C15 7.3431 13.6569 6 12 6C10.3431 6 9 7.3431 9 9C9 10.6569 10.3431 12 12 12C13.6569 12 15 10.6569 15 9ZM13 9C13 9.5523 12.5523 10 12 10C11.4477 10 11 9.5523 11 9C11 8.4477 11.4477 8 12 8C12.5523 8 13 8.4477 13 9Z");
  stroke: none;
}

.knxfuxbru {
  d: path("M22 12L22 4C22 2.8954 21.1046 2 20 2L4 2C2.8954 2 2 2.8954 2 4L2 14C2 15.1046 2.8954 16 4 16L12 16M18 2C18 3.3333 18.8 6 22 6M6 16C6 14.6667 5.2 12 2 12M6 2C6 3.3333 5.2 6 2 6M22 16L16 22M16 16L22 22");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

</style>
