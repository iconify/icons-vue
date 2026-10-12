<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><path class="evy345wtm"/><path class="f6by3i7af"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:fabric-roll-sharp" /></template>
<style>
.evy345wtm {
  d: path("M2.75 3.25h18.5v6H2.75z");
}

.f6by3i7af {
  d: path("M6.5 3.75a1.5 2.5 0 0 1 0 5m-.5 3h12.5v9.5l-.43-.25l-1.31-.75l-.43-.25l-.43.25l-1.3.75l-.43.25l-.43-.25l-1.31-.75L12 20l-.43.25l-1.31.75l-.43.25L9.4 21l-1.3-.75l-.43-.25l-.43.25l-1.31.75l-.43.25v-9.5z");
}

.x2cwu0gfd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
