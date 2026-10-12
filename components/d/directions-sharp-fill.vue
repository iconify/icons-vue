<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="gp_8x1bzb"><path class="mudtzwb8g"/><path class="uob2i8b3s"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:directions-sharp-fill" /></template>
<style>
.gp_8x1bzb {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.mudtzwb8g {
  fill: currentColor;
  d: path("M16 19C16 21.2091 14.2091 23 12 23C9.7909 23 8 21.2091 8 19C8 16.7909 9.7909 15 12 15C14.2091 15 16 16.7909 16 19Z");
  stroke: none;
}

.uob2i8b3s {
  d: path("M12 16C12 13.7909 13.7909 12 16 12L22 12M18.7071 8.7071L22 12L18.7071 15.2929M12 10L12 2M8.7071 5.2929L12 2L15.2929 5.2929M10 12L2 12M5.2929 15.2929L2 12L5.2929 8.7071");
}

</style>
