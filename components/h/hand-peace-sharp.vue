<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><path class="dh0rxobaa"/><path class="cy8tfnbwa"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:hand-peace-sharp" /></template>
<style>
.cy8tfnbwa {
  d: path("M14.25 13.5h-2.5l-1.5 1.5m3.55-4.25v2");
}

.dh0rxobaa {
  d: path("M6.25 14V3.25h2.5V11h2.5V3.25h2.5v8.25h.15V9.9h3.2V16a5.25 5.25 0 0 1-5.25 5.25H6.3v-4.5Z");
}

.x2cwu0gfd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
