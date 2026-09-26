<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path clip-rule="evenodd" class="db2g8rb1n"/><path class="xu9a9gb7p"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:app-window-minus-fill" /></template>
<style>
.db2g8rb1n {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M6 2L18 2C20.2091 2 22 3.7909 22 6L22 11C22 11.5523 21.5523 12 21 12L15 12C13.3431 12 12 13.3431 12 15L12 21C12 21.5523 11.5523 22 11 22L6 22C3.7909 22 2 20.2091 2 18L2 6C2 3.7909 3.7909 2 6 2ZM8 7C8 6.4477 7.5523 6 7 6C6.4477 6 6 6.4477 6 7C6 7.5523 6.4477 8 7 8C7.5523 8 8 7.5523 8 7ZM12 7C12 6.4477 11.5523 6 11 6C10.4477 6 10 6.4477 10 7C10 7.5523 10.4477 8 11 8C11.5523 8 12 7.5523 12 7ZM16 7C16 6.4477 15.5523 6 15 6C14.4477 6 14 6.4477 14 7C14 7.5523 14.4477 8 15 8C15.5523 8 16 7.5523 16 7Z");
  stroke: none;
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.xu9a9gb7p {
  d: path("M15 18H21");
}

</style>
