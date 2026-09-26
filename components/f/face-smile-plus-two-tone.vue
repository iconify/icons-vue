<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="pqm17jbcd"/><path class="ku5_4yd7s"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:face-smile-plus-two-tone" /></template>
<style>
.ku5_4yd7s {
  d: path("M9 10L9 11M15 10L15 11M9 15C10 16 11 16.5 12 16.5C13 16.5 14 16 15 15M19 2L19 8M16 5L22 5");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.pqm17jbcd {
  stroke-opacity: 0.4;
  d: path("M22 12C22 17.5228 17.5228 22 12 22C6.4772 22 2 17.5228 2 12C2 6.4772 6.4772 2 12 2");
}

</style>
