<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="mt2-x739s"/><path class="nx_se2bof"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:file-alert" /></template>
<style>
.mt2-x739s {
  d: path("M14 2L8 2C5.7909 2 4 3.7909 4 6L4 18C4 20.2091 5.7909 22 8 22L10 22M14 2L20 8L20 12M14 2L14 5C14 6.6569 15.3431 8 17 8L20 8M17 16L17 18");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.nx_se2bof {
  fill: currentColor;
  d: path("M18 22C18 22.5523 17.5523 23 17 23C16.4477 23 16 22.5523 16 22C16 21.4477 16.4477 21 17 21C17.5523 21 18 21.4477 18 22Z");
  stroke: none;
}

</style>
