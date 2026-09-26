<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="a9swe9sgn"/><path class="nj9ik1bul"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:bookmark-two-tone" /></template>
<style>
.a9swe9sgn {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M3 5C3 2.7909 4.7909 1 7 1L17 1C19.2091 1 21 2.7909 21 5L21 20.9983C21 22.5807 19.2495 23.532 17.9185 22.6807L12.2704 19.6926C12.1057 19.5867 11.8943 19.5867 11.7296 19.6926L6.0815 22.6807C4.7505 23.532 3 22.5807 3 20.9983Z");
  stroke: none;
}

.nj9ik1bul {
  d: path("M4 5C4 3.3431 5.3431 2 7 2L17 2C18.6569 2 20 3.3431 20 5L20 20.9983C20 21.7895 19.1248 22.2673 18.4592 21.8395L12.8111 18.8514C12.317 18.5338 11.683 18.5338 11.1889 18.8514L5.5408 21.8395C4.8752 22.2673 4 21.7895 4 20.9983Z");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

</style>
