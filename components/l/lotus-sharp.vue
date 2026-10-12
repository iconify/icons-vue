<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><path class="q5vf9fb3i"/><path class="l0ovr7baw"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:lotus-sharp" /></template>
<style>
.l0ovr7baw {
  d: path("M8.75 9.5C7 8.5 5 8.25 3 8.5c.25 5.5 4 9.25 9 9.25S20.75 14 21 8.5c-2-.25-4 0-5.75 1M5.5 21.25h13");
}

.q5vf9fb3i {
  d: path("M12 3.5c2.25 2 3.25 4.5 3.25 7.25s-1.25 3-3.25 4.5c-2-1.25-3.25-3-3.25-5.5S9.75 5.5 12 3.5Z");
}

.x2cwu0gfd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
