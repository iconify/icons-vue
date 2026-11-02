<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="ky40s1frt"/><path class="z9g2aviji"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:apple-duocolor" /></template>
<style>
.ky40s1frt {
  stroke-opacity: 0.4;
  d: path("M12 10V6m0 0c.325-2.175 3.483-3.267 7-2c-2.317 2.933-5.575 3.675-7 2");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.z9g2aviji {
  d: path("M12 10a5 5 0 0 1 8 4c0 3.5-2 7-5 7c-1 0-2-1-3-1s-2 1-3 1c-3 0-5-3.5-5-7a5 5 0 0 1 8-4");
}

</style>
