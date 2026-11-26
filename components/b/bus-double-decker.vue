<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="hidj5821c"/><path clip-rule="evenodd" class="v8bb7zbok"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:bus-double-decker" /></template>
<style>
.hidj5821c {
  d: path("M4 20L4 6C4 3.7909 5.7909 2 8 2L16 2C18.2091 2 20 3.7909 20 6L20 20ZM4 6L20 6M2 12L22 12M12 6L12 12M4 20L4 21C4 21.5523 4.4477 22 5 22L7 22C7.5523 22 8 21.5523 8 21L8 20M16 20L16 21C16 21.5523 16.4477 22 17 22L19 22C19.5523 22 20 21.5523 20 21L20 20");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.v8bb7zbok {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M9 16C9 16.5523 8.5523 17 8 17C7.4477 17 7 16.5523 7 16C7 15.4477 7.4477 15 8 15C8.5523 15 9 15.4477 9 16ZM17 16C17 16.5523 16.5523 17 16 17C15.4477 17 15 16.5523 15 16C15 15.4477 15.4477 15 16 15C16.5523 15 17 15.4477 17 16Z");
  stroke: none;
}

</style>
