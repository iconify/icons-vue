<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="gp_8x1bzb"><path class="hy82feb9n"/><path class="rutkrebqi"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:coffee-sharp-fill" /></template>
<style>
.gp_8x1bzb {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.hy82feb9n {
  fill: currentColor;
  d: path("M4 10L16 10C16.5523 10 17 10.4477 17 11L17 22C17 22.5523 16.5523 23 16 23L4 23C3.4477 23 3 22.5523 3 22L3 11C3 10.4477 3.4477 10 4 10Z");
  stroke: none;
}

.rutkrebqi {
  d: path("M16 13L17 13C18.6569 13 20 14.3431 20 16C20 17.6569 18.6569 19 17 19L16 19M8.5 7L8.5 6C8.5 5.2131 8.8705 4.4721 9.5 4C10.1295 3.5279 10.5 2.7869 10.5 2L10.5 1M13.5 7L13.5 6C13.5 5.2131 13.8705 4.4721 14.5 4C15.1295 3.5279 15.5 2.7869 15.5 2L15.5 1");
}

</style>
