<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="pdkikdubk"/><path clip-rule="evenodd" class="xawcu0b-g"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:flow-documents-duotone" /></template>
<style>
.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.pdkikdubk {
  stroke-opacity: 0.4;
  d: path("M2 12L2 8C2 6.3431 3.3431 5 5 5L15 5");
}

.xawcu0b-g {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M14 8L19 8C21.2092 8 23 9.7908 23 12L23 14.8038C23 15.9084 22.1046 16.8038 21 16.8038C20.649 16.8038 20.3042 16.7114 20.0002 16.5361C19.3919 16.1848 18.7022 16 18 16C16.741 16 15.5554 16.5928 14.8 17.6C13.6668 19.1108 11.8886 20 10 20C8.278 20 6.639 19.2601 5.5 17.9687C5.1778 17.6033 5 17.1329 5 16.6458L5 12C5 9.7908 6.7908 8 9 8Z");
  stroke: none;
}

</style>
