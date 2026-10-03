<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="gp_8x1bzb"><path class="tb0l1cb3r"/><path class="nx_se2bof"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:file-alert-sharp" /></template>
<style>
.gp_8x1bzb {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.nx_se2bof {
  fill: currentColor;
  d: path("M18 22C18 22.5523 17.5523 23 17 23C16.4477 23 16 22.5523 16 22C16 21.4477 16.4477 21 17 21C17.5523 21 18 21.4477 18 22Z");
  stroke: none;
}

.tb0l1cb3r {
  d: path("M14 2L4 2L4 22L11 22M14 2L20 8L20 13M14 2L14 8L20 8M17 15L17 19");
}

</style>
