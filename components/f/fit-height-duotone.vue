<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="s57z5lq7h"/><path class="ydeasn-sq"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:fit-height-duotone" /></template>
<style>
.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.s57z5lq7h {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M21 12L21 19C21 21.2092 19.2092 23 17 23L7 23C4.7908 23 3 21.2092 3 19L3 5C3 2.7908 4.7908 1 7 1L17 1C19.2092 1 21 2.7908 21 5Z");
  stroke: none;
}

.ydeasn-sq {
  d: path("M12 6V18M9 9L12 6L15 9M9 15L12 18L15 15");
}

</style>
