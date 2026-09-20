<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="a3wmb4ndd"/><path class="a86gg4zyi"/><path class="m2xj7dbwz"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:anniversary-outline-regular" /></template>
<style>
.a3wmb4ndd {
  d: path("M12 17c-3 -2 -7 -4.5 -5.5 -7.5 1.5 -2 4 -1 5.5 1 1.5 -2 4 -3 5.5 -1C19 12.5 15 15 12 17");
}

.a86gg4zyi {
  d: path("M4 12a8 8 0 1 1 4 7");
}

.m2xj7dbwz {
  d: path("m2 10 2 2 2 -2");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

</style>
