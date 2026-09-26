<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="v_plwqrob"/><path class="xs7teru1d"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:git-refresh-fill" /></template>
<style>
.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.v_plwqrob {
  d: path("M6 21V9M18 13V10C18 7.79086 16.2091 6 14 6H13M13.5 17.5H17.5C19.433 17.5 21 19.067 21 21M14.5 15.5L12.8536 17.1464C12.6583 17.3417 12.6583 17.6583 12.8536 17.8536L14.5 19.5");
}

.xs7teru1d {
  fill: currentColor;
  d: path("M10 6C10 8.20914 8.20914 10 6 10C3.79086 10 2 8.20914 2 6C2 3.79086 3.79086 2 6 2C8.20914 2 10 3.79086 10 6Z");
  stroke: none;
}

</style>
