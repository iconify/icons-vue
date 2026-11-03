<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="jtz6wyb4m"/><path class="g23rx1qht"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:briefcase-arrow-down-duotone" /></template>
<style>
.g23rx1qht {
  d: path("M8.5 6L8.5 5C8.5 3.3431 9.8431 2 11.5 2L12.5 2C14.1569 2 15.5 3.3431 15.5 5L15.5 6M12 10L12 14M9 11L12 14L15 11M3 22L21 22");
}

.jtz6wyb4m {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M6 5L18 5C20.2092 5 22 6.7908 22 9L22 15C22 17.2092 20.2092 19 18 19L6 19C3.7908 19 2 17.2092 2 15L2 9C2 6.7908 3.7908 5 6 5Z");
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
