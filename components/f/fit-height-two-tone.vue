<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="s57z5lq7h"/><path class="ewx0suy2w"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:fit-height-two-tone" /></template>
<style>
.ewx0suy2w {
  d: path("M7 2L17 2C18.6569 2 20 3.3431 20 5L20 19C20 20.6569 18.6569 22 17 22L7 22C5.3431 22 4 20.6569 4 19L4 5C4 3.3431 5.3431 2 7 2ZM12 6V18M9 9L12 6L15 9M9 15L12 18L15 15");
}

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

</style>
