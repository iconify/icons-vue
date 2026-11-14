<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="noymtrbyh"/><path class="b5aqaab9e"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:day-of-dead-skull" /></template>
<style>
.b5aqaab9e {
  d: path("M10.75 6a1.25 1.25 0 0 1 2.5 0a1.25 1.25 0 0 1 0 2.5a1.25 1.25 0 0 1-2.5 0a1.25 1.25 0 0 1 0-2.5Zm-4.5 6.75a1.75 1.75 0 1 0 3.5 0a1.75 1.75 0 1 0-3.5 0Zm8 0a1.75 1.75 0 1 0 3.5 0a1.75 1.75 0 1 0-3.5 0Z");
}

.noymtrbyh {
  d: path("M12 2.5a8.5 8.5 0 0 1 8.5 8.5v3.5a2 2 0 0 1-2 2h-2V20a1.5 1.5 0 0 1-1.5 1.5H9A1.5 1.5 0 0 1 7.5 20v-3.5h-2a2 2 0 0 1-2-2V11A8.5 8.5 0 0 1 12 2.5Z");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
