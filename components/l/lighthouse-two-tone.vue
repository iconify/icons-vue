<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="coe06pp_e"/><path class="gg4x98pww"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:lighthouse-two-tone" /></template>
<style>
.coe06pp_e {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M16 8.9235L17.9884 21.8479C17.9961 21.8983 18 21.9491 18 22C18 22.5523 17.5523 23 17 23L7 23C6.4477 23 6 22.5523 6 22C6 21.9491 6.0039 21.8983 6.0116 21.8479L8 8.9235L8 5C8 4.7636 8.0837 4.5349 8.2363 4.3544L10.4726 1.7089C10.8526 1.2594 11.4114 1.0001 12 1.0001C12.5886 1.0001 13.1474 1.2594 13.5274 1.7089L15.7637 4.3544C15.9163 4.5349 16 4.7636 16 5L16 8.9235Z");
  stroke: none;
}

.gg4x98pww {
  d: path("M9 9L9 5L11.2363 2.3545C11.6358 1.8819 12.3642 1.8819 12.7637 2.3545L15 5L15 9L9 9ZM9 5L15 5M7 9L17 9M9 9L7 22M15 9L17 22M8.3846 13L15.6154 13M7.6923 17.5L16.3077 17.5M4 22L20 22M22 3L20 4M20 14L22 15M21 9L22 9M2 3L4 4M4 14L2 15M3 9L2 9");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

</style>
