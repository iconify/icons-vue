<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="vhxs2pbdc"/><path class="rfcbg6cch"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:key-off-two-tone" /></template>
<style>
.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.rfcbg6cch {
  d: path("M10 12C10 14.2091 8.2091 16 6 16C3.7909 16 2 14.2091 2 12C2 9.7909 3.7909 8 6 8C8.2091 8 10 9.7909 10 12ZM10 12H12M12 12L2 2M12 12L22 22");
}

.vhxs2pbdc {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M10.8723 10.8724C10.9559 11.2347 11 11.6122 11 12C11 14.7614 8.7614 17 6 17C3.2386 17 1 14.7614 1 12C1 9.2386 3.2386 7 6 7C6.3878 7 6.7653 7.0441 7.1276 7.1277L10.8723 10.8724ZM21 11H22C22.5523 11 23 11.4477 23 12C23 12.5523 22.5523 13 22 13V15.3431C22 15.8954 21.5523 16.3431 21 16.3431C20.4477 16.3431 20 15.8954 20 15.3431V13H17.6569C17.1046 13 16.6569 12.5523 16.6569 12C16.6569 11.4477 17.1046 11 17.6569 11H21Z");
  stroke: none;
}

</style>
