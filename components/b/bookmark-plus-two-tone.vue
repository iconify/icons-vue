<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="eklrzq3bx"/><path class="qxsi3gbjx"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:bookmark-plus-two-tone" /></template>
<style>
.eklrzq3bx {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M3 5C3 2.7909 4.7909 1 7 1L10 1C10.5523 1 11 1.4477 11 2L11 8C11 9.6569 12.3431 11 14 11L20 11C20.5523 11 21 11.4477 21 12L21 20.9983C21 22.5807 19.2495 23.532 17.9185 22.6807L12.2704 19.6926C12.1057 19.5867 11.8943 19.5867 11.7296 19.6926L6.0815 22.6807C4.7505 23.532 3 22.5807 3 20.9983Z");
  stroke: none;
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.qxsi3gbjx {
  d: path("M20 12L20 20.9983C20 21.7895 19.1248 22.2673 18.4592 21.8395L12.8111 18.8514C12.317 18.5338 11.683 18.5338 11.1889 18.8514L5.5408 21.8395C4.8752 22.2673 4 21.7895 4 20.9983L4 5C4 3.3431 5.3431 2 7 2L10 2M17 2V8M14 5H20");
}

</style>
