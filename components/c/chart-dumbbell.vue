<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="jvz7t0bpz"/><path class="i4rwz0bqe"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:chart-dumbbell" /></template>
<style>
.i4rwz0bqe {
  fill: currentColor;
  d: path("M3 5a2 2 0 1 0 4 0a2 2 0 1 0-4 0Zm10 0a2 2 0 1 0 4 0a2 2 0 1 0-4 0Zm-6 7a2 2 0 1 0 4 0a2 2 0 1 0-4 0Zm10.5 0a2 2 0 1 0 4 0a2 2 0 1 0-4 0Zm-15 7a2 2 0 1 0 4 0a2 2 0 1 0-4 0ZM15 19a2 2 0 1 0 4 0a2 2 0 1 0-4 0Z");
}

.jvz7t0bpz {
  d: path("M6 5h8m-4 7h9M5 19h11.5");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
