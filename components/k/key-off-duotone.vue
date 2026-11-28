<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="gb3rx2yvn"/><path class="ayo73pbzj"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:key-off-duotone" /></template>
<style>
.ayo73pbzj {
  d: path("M2 2L22 22");
}

.gb3rx2yvn {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M12.6446 12.7646C12.4705 12.9115 12.2456 13 12 13H10.9C10.4367 15.2822 8.4189 17 6 17C3.2386 17 1 14.7614 1 12C1 9.2386 3.2386 7 6 7C6.3336 7 6.6597 7.0326 6.975 7.095L12.6446 12.7646ZM21 11H22C22.5523 11 23 11.4477 23 12C23 12.5523 22.5523 13 22 13V15.3431C22 15.8954 21.5523 16.3431 21 16.3431C20.4477 16.3431 20 15.8954 20 15.3431V13H17.6569C17.1046 13 16.6569 12.5523 16.6569 12C16.6569 11.4477 17.1046 11 17.6569 11H21Z");
  stroke: none;
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

</style>
