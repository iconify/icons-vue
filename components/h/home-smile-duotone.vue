<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="p7mh2_5vc"/><path class="vs--dsbzx"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:home-smile-duotone" /></template>
<style>
.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.p7mh2_5vc {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M10.0605 2.7073C11.1795 1.7593 12.8205 1.7593 13.9395 2.7073L20.9395 8.6379L21.0615 8.7483C21.6586 9.3132 22 10.1004 22 10.927L22 19.0002C21.9999 20.657 20.6568 22.0002 19 22.0002L5 22.0002C3.3432 22.0002 2.0001 20.657 2 19.0002L2 10.927C2 10.0454 2.3878 9.208 3.0606 8.6379L10.0605 2.7073Z");
  stroke: none;
}

.vs--dsbzx {
  d: path("M9 10.5L9 11.5M15 10.5L15 11.5M9 15.5C10 16.5 11 17 12 17C13 17 14 16.5 15 15.5");
}

</style>
