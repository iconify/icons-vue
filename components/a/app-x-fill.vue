<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path clip-rule="evenodd" class="djkklnbjb"/><path class="j9vsk2b8a"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:app-x-fill" /></template>
<style>
.djkklnbjb {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M6 2H18C20.2091 2 22 3.79086 22 6V11C22 11.5523 21.5523 12 21 12H15C13.3431 12 12 13.3431 12 15V21C12 21.5523 11.5523 22 11 22H6C3.79086 22 2 20.2091 2 18V6C2 3.79086 3.79086 2 6 2Z");
  stroke: none;
}

.j9vsk2b8a {
  d: path("M15 15L21 21M21 15L15 21");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

</style>
