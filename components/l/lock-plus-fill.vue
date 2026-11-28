<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="smi4ruzkp"/><path clip-rule="evenodd" class="crb_j-b2k"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:lock-plus-fill" /></template>
<style>
.crb_j-b2k {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M17 9C19.2091 9 21 10.7909 21 13L21 19C21 21.2091 19.2091 23 17 23L7 23C4.7909 23 3 21.2091 3 19L3 13C3 10.7909 4.7909 9 7 9ZM13 17L14 17C14.5523 17 15 16.5523 15 16C15 15.4477 14.5523 15 14 15L13 15L13 14C13 13.4477 12.5523 13 12 13C11.4477 13 11 13.4477 11 14L11 15L10 15C9.4477 15 9 15.4477 9 16C9 16.5523 9.4477 17 10 17L11 17L11 18C11 18.5523 11.4477 19 12 19C12.5523 19 13 18.5523 13 18Z");
  stroke: none;
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.smi4ruzkp {
  d: path("M7.5 10V6.5C7.5 4.01472 9.51472 2 12 2C14.4853 2 16.5 4.01472 16.5 6.5V10");
}

</style>
