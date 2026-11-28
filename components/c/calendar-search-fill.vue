<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path clip-rule="evenodd" class="mdxec8bcx"/><path class="j5i7d5sbn"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:calendar-search-fill" /></template>
<style>
.j5i7d5sbn {
  d: path("M8 3V7M16 3V7M20 17.5C20 18.8807 18.8807 20 17.5 20C16.1193 20 15 18.8807 15 17.5C15 16.1193 16.1193 15 17.5 15C18.8807 15 20 16.1193 20 17.5ZM19.5 19.5L21 21");
}

.mdxec8bcx {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M6 4L18 4C20.2091 4 22 5.7909 22 8L22 11C22 11.5523 21.5523 12 21 12L15 12C13.3431 12 12 13.3431 12 15L12 21C12 21.5523 11.5523 22 11 22L6 22C3.7909 22 2 20.2091 2 18L2 8C2 5.7909 3.7909 4 6 4ZM7 10C6.4477 10 6 10.4477 6 11C6 11.5523 6.4477 12 7 12L17 12C17.5523 12 18 11.5523 18 11C18 10.4477 17.5523 10 17 10Z");
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
