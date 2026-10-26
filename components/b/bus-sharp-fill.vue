<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="gp_8x1bzb"><path class="zvwgdpb9a"/><path class="b4xnk8z4d"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:bus-sharp-fill" /></template>
<style>
.b4xnk8z4d {
  d: path("M9 18L15 18M9 18C9 19.1046 8.1046 20 7 20C5.8954 20 5 19.1046 5 18C5 16.8954 5.8954 16 7 16C8.1046 16 9 16.8954 9 18ZM19 18C19 19.1046 18.1046 20 17 20C15.8954 20 15 19.1046 15 18C15 16.8954 15.8954 16 17 16C18.1046 16 19 16.8954 19 18ZM5 18L2 18L2 4L17.964 4C20.4802 5.6253 22 8.4163 22 11.4118L22 18L19 18M14 4L14 9L17 12L22 12M14 9L2 9M8 9L8 4");
}

.gp_8x1bzb {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.zvwgdpb9a {
  fill: currentColor;
  d: path("M15 18L9 18C9 16.8954 8.1046 16 7 16C5.8954 16 5 16.8954 5 18L2 18L2 9L14 9L17 12L22 12L22 18L19 18C19 16.8954 18.1046 16 17 16C15.8954 16 15 16.8954 15 18Z");
  stroke: none;
}

</style>
