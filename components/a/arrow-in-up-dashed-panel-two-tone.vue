<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="j-34asx2t"/><path class="p1ke-ubua"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:arrow-in-up-dashed-panel-two-tone" /></template>
<style>
.j-34asx2t {
  stroke-opacity: 0.4;
  d: path("M3 6C3 4.34315 4.34315 3 6 3M10.5 3H13.5M21 7V6.00026C21 4.34341 19.6569 3 18 3M7 21H6C4.34315 21 3 19.6569 3 18M3 10.5V13.5");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.p1ke-ubua {
  d: path("M15.5 11V21M10 16L15.1314 10.4021C15.3296 10.1859 15.6704 10.1859 15.8686 10.4021L21 16");
}

</style>
