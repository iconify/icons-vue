<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="edstwtszr"/><path class="teqqe-b2q"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:git-join-duotone" /></template>
<style>
.edstwtszr {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M9 5C9 7.20914 7.20914 9 5 9C2.79086 9 1 7.20914 1 5C1 2.79086 2.79086 1 5 1C7.20914 1 9 2.79086 9 5ZM23 5C23 7.20914 21.2091 9 19 9C16.7909 9 15 7.20914 15 5C15 2.79086 16.7909 1 19 1C21.2091 1 23 2.79086 23 5ZM16 19C16 21.2091 14.2091 23 12 23C9.79086 23 8 21.2091 8 19C8 16.7909 9.79086 15 12 15C14.2091 15 16 16.7909 16 19Z");
  stroke: none;
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.teqqe-b2q {
  d: path("M12 16V11M5 8C5 9.65685 6.34315 11 8 11H16C17.6569 11 19 9.65685 19 8");
}

</style>
