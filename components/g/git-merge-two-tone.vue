<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="ggrpqy6eh"/><path class="e82gl2bak"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:git-merge-two-tone" /></template>
<style>
.e82gl2bak {
  d: path("M6 3V15C6.16667 12 8.2 6 15 6M6 21C7.65685 21 9 19.65685 9 18C9 16.34315 7.65685 15 6 15C4.34315 15 3 16.34315 3 18C3 19.65685 4.34315 21 6 21ZM18 9C19.6569 9 21 7.6569 21 6C21 4.3431 19.6569 3 18 3C16.3431 3 15 4.3431 15 6C15 7.6569 16.3431 9 18 9Z");
}

.ggrpqy6eh {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M10 18C10 15.79086 8.20914 14 6 14C3.79086 14 2 15.79086 2 18C2 20.20914 3.79086 22 6 22C8.20914 22 10 20.20914 10 18ZM22 6C22 3.79086 20.20914 2 18 2C15.79086 2 14 3.79086 14 6C14 8.20914 15.79086 10 18 10C20.20914 10 22 8.20914 22 6Z");
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
