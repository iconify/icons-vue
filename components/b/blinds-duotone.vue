<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="rqu5aejpc"/><path class="vt761abvf"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:blinds-duotone" /></template>
<style>
.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.rqu5aejpc {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M21 3.0001L21 11C21 13.2092 19.2092 15 17 15L7 15C4.7908 15 3 13.2092 3 11L3 3.0001L2 3.0001C1.4477 3.0001 1 2.5524 1 2.0001C1 1.4478 1.4477 1.0001 2 1.0001L3.988 1.0001C3.992 1 3.996 1 4 1L20 1C20.004 1 20.008 1 20.012 1.0001L22 1.0001C22.5523 1.0001 23 1.4478 23 2.0001C23 2.5524 22.5523 3.0001 22 3.0001L21 3.0001Z");
  stroke: none;
}

.vt761abvf {
  d: path("M8 6L16 6M8 10L16 10M12 14L12 18M14 20C14 21.1046 13.1046 22 12 22C10.8954 22 10 21.1046 10 20C10 18.8954 10.8954 18 12 18C13.1046 18 14 18.8954 14 20Z");
}

</style>
