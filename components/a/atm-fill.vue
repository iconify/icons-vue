<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path clip-rule="evenodd" class="e9rqvyuim"/><path class="rj4pp1bwf"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:atm-fill" /></template>
<style>
.e9rqvyuim {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M19 11L19 18C19 19.6569 17.6569 21 16 21L8 21C6.3431 21 5 19.6569 5 18L5 4C5 3.4477 5.4477 3 6 3L18 3C18.5523 3 19 3.4477 19 4ZM15 12C15 10.3431 13.6569 9 12 9C10.3431 9 9 10.3431 9 12C9 13.6569 10.3431 15 12 15C13.6569 15 15 13.6569 15 12ZM13 12C13 12.5523 12.5523 13 12 13C11.4477 13 11 12.5523 11 12C11 11.4477 11.4477 11 12 11C12.5523 11 13 11.4477 13 12Z");
  stroke: none;
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.rj4pp1bwf {
  d: path("M6 4L4 4C2.8954 4 2 4.8954 2 6L2 8C2 9.1046 2.8954 10 4 10L6 10M18 4L20 4C21.1046 4 22 4.8954 22 6L22 8C22 9.1046 21.1046 10 20 10L18 10");
}

</style>
