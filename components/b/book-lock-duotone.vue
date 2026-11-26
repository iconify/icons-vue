<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="k851pumqo"/><path class="m0cijpkwe"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:book-lock-duotone" /></template>
<style>
.k851pumqo {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M7 1L17 1C19.2091 1 21 2.7909 21 5L21 9C21 9.5523 20.5523 10 20 10L13 10C11.3431 10 10 11.3431 10 13L10 22C10 22.5523 9.5523 23 9 23L6 23C4.3431 23 3 21.6569 3 20L3 5C3 2.7909 4.7909 1 7 1Z");
  stroke: none;
}

.m0cijpkwe {
  d: path("M4 20C4 18.8954 4.8954 18 6 18L9 18M8 6L8 14M14 17L19 17C19.5523 17 20 17.4477 20 18L20 21C20 21.5523 19.5523 22 19 22L14 22C13.4477 22 13 21.5523 13 21L13 18C13 17.4477 13.4477 17 14 17ZM14.5 17L14.5 15C14.5 13.8954 15.3954 13 16.5 13C17.6046 13 18.5 13.8954 18.5 15L18.5 17");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

</style>
