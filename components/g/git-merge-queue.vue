<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="e82gl2bak"/><path class="neqj4sb0x"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:git-merge-queue" /></template>
<style>
.e82gl2bak {
  d: path("M6 3V15C6.16667 12 8.2 6 15 6M6 21C7.65685 21 9 19.65685 9 18C9 16.34315 7.65685 15 6 15C4.34315 15 3 16.34315 3 18C3 19.65685 4.34315 21 6 21ZM18 9C19.6569 9 21 7.6569 21 6C21 4.3431 19.6569 3 18 3C16.3431 3 15 4.3431 15 6C15 7.6569 16.3431 9 18 9Z");
}

.neqj4sb0x {
  fill: currentColor;
  d: path("M19.5 14C19.5 14.8284 18.8284 15.5 18 15.5C17.1716 15.5 16.5 14.8284 16.5 14C16.5 13.1716 17.1716 12.5 18 12.5C18.8284 12.5 19.5 13.1716 19.5 14ZM19.5 19.5C19.5 20.3284 18.8284 21 18 21C17.1716 21 16.5 20.3284 16.5 19.5C16.5 18.6716 17.1716 18 18 18C18.8284 18 19.5 18.6716 19.5 19.5Z");
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
