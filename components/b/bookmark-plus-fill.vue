<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="ld_8bhyht"/><path class="a0-3src4f"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:bookmark-plus-fill" /></template>
<style>
.a0-3src4f {
  d: path("M17 2V8M14 5H20");
}

.ld_8bhyht {
  fill: currentColor;
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

</style>
