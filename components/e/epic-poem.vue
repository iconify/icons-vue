<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="bylrybb2b"/><path class="vzbl55r-b"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:epic-poem" /></template>
<style>
.bylrybb2b {
  d: path("M8 8H3V5.5A2.5 2.5 0 0 1 5.5 3H15a2.5 2.5 0 0 1 2.5 2.5V16");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.vzbl55r-b {
  d: path("M5.5 3A2.5 2.5 0 0 1 8 5.5v13a2.5 2.5 0 0 0 2.5 2.5h8a2.5 2.5 0 0 0 2.5-2.5V16H10.5v2.5A2.5 2.5 0 0 1 8 21m3-13h3.5M11 12h3.5");
}

</style>
