<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path clip-rule="evenodd" class="gpj46ncei"/><path class="xofc3l91p"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:bottle-pump-fill" /></template>
<style>
.gpj46ncei {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M8.1135 6.9267C8.3456 6.3657 8.8929 5.9999 9.5 6L14.5 6C15.1071 5.9999 15.6544 6.3657 15.8865 6.9267C15.8883 6.9511 15.8892 6.9756 15.8892 7C15.8892 7.5523 15.4415 8 14.8892 8L9.1108 8C8.5585 8 8.1108 7.5523 8.1108 7C8.1108 6.9756 8.1117 6.9511 8.1135 6.9267ZM9 10L15 10C17.2092 10 19 11.7908 19 14L19 19C19 21.2092 17.2092 23 15 23L9 23C6.7908 23 5 21.2092 5 19L5 14C5 11.7908 6.7908 10 9 10Z");
  stroke: none;
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.xofc3l91p {
  d: path("M12 2L12 7M9 2L13.1716 2C14.9826 2 16.7194 2.7194 18 4");
}

</style>
