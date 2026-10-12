<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="r55cn8bej"/><path class="l6lh2bb2i"/><path class="gau01kfhc"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:directions-duotone" /></template>
<style>
.gau01kfhc {
  d: path("M12 16C12 13.7909 13.7909 12 16 12L22 12M19 9L22 12L19 15");
}

.l6lh2bb2i {
  stroke-opacity: 0.4;
  d: path("M12 9L12 2M9 5L12 2L15 5M9 12L2 12M5 15L2 12L5 9");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.r55cn8bej {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M16 19C16 21.2091 14.2091 23 12 23C9.7909 23 8 21.2091 8 19C8 16.7909 9.7909 15 12 15C14.2091 15 16 16.7909 16 19Z");
  stroke: none;
}

</style>
