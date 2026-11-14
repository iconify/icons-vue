<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="pv8wodgif"/><path class="agavl4_2e"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:beer-growler" /></template>
<style>
.agavl4_2e {
  d: path("M14.5 4H16a2 2 0 0 1 2 2v4.5m-9.5 2h7v5h-7Z");
}

.pv8wodgif {
  d: path("M9.5 2.5h5V5c0 1.5 3.5 2.5 3.5 5.5v9a1.5 1.5 0 0 1-1.5 1.5h-9A1.5 1.5 0 0 1 6 19.5v-9c0-3 3.5-4 3.5-5.5Z");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
