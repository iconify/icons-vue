<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="gp_8x1bzb"><path class="jv4nm4dgg"/><path class="lin_3l6lc"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:comma-sharp" /></template>
<style>
.gp_8x1bzb {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.jv4nm4dgg {
  d: path("M13 10C13 12 12 14 11 15L10.7071 15.2929");
}

.lin_3l6lc {
  fill: currentColor;
  d: path("M14 10C14 11.1046 13.1046 12 12 12C10.8954 12 10 11.1046 10 10C10 8.8954 10.8954 8 12 8C13.1046 8 14 8.8954 14 10Z");
  stroke: none;
}

</style>
