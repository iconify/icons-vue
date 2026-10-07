<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="gp_8x1bzb"><path clip-rule="evenodd" class="kejub7uii"/><path class="ahhqo1b4s"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:image-off-sharp-duotone" /></template>
<style>
.ahhqo1b4s {
  d: path("M1.7071 1.7071L22.2929 22.2929");
}

.gp_8x1bzb {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.kejub7uii {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  fill-rule: evenodd;
  d: path("M21.7071 21.7071C21.5198 21.8949 21.2653 22.0003 21 22L3 22C2.4477 22 2 21.5523 2 21L2 3C1.9997 2.7347 2.1051 2.4802 2.2929 2.2929L14.7143 14.7143L13 16L9.7071 12.7071C9.5196 12.5196 9.2652 12.4142 9 12.4142C8.7348 12.4142 8.4804 12.5196 8.2929 12.7071L4 17L4 19C4 19.5523 4.4477 20 5 20L19 20C19.2653 20.0003 19.5198 19.8949 19.7071 19.7071L21.7071 21.7071ZM5.6569 2L21 2C21.5523 2 22 2.4477 22 3L22 18.3431L5.6569 2Z");
  stroke: none;
}

</style>
