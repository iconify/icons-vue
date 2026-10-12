<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><path class="zrf8f-y4q"/><path class="wldf59bdw"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:camera-flip-sharp" /></template>
<style>
.wldf59bdw {
  d: path("M8.75 13a3.25 3.25 0 0 1 5.9-1.9m.6 2.4a3.25 3.25 0 0 1-5.9 1.9M14.9 9v2.25h-2.25m-3.55 6.5V15.5h2.25");
}

.x2cwu0gfd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.zrf8f-y4q {
  d: path("M3.25 9.25v-2h4.1l1.1-1.85l.433-.751l.867.001h4.5l.867-.001l.433.751l1.1 1.85h4.1v13H3.25v-2.5Z");
}

</style>
