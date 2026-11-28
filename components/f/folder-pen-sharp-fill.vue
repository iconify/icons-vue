<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="gp_8x1bzb"><path class="swbz2abyd"/><path clip-rule="evenodd" class="dqpr9gbdx"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:folder-pen-sharp-fill" /></template>
<style>
.dqpr9gbdx {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M14.757 13.219L16.879 11.097C17.441 10.535 18.204 10.219 19 10.219C20.657 10.219 22 11.562 22 13.219C22 14.014 21.684 14.777 21.121 15.34L16.879 19.583C16.758 19.703 16.609 19.791 16.445 19.837L12.492 20.962C12.403 20.987 12.311 21 12.219 21C11.667 21 11.219 20.552 11.219 20C11.219 19.907 11.232 19.815 11.257 19.726L12.381 15.773C12.428 15.61 12.515 15.46 12.636 15.34L14.757 13.219Z");
  stroke: none;
}

.gp_8x1bzb {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.swbz2abyd {
  d: path("M9.384 20H3V4H9.5L12 6.5H21V8.562");
}

</style>
