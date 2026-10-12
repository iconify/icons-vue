<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="rautkib6l"/><path class="i3x2w36av"/><circle class="yakkvabqx"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:folder-music" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.i3x2w36av {
  d: path("M12.75 16.75V10L15 11.5");
}

.rautkib6l {
  d: path("M2.75 7.25a2.5 2.5 0 0 1 2.5-2.5h3.6a2 2 0 0 1 1.6.8L11.55 7a2 2 0 0 0 1.6.8h5.6a2.5 2.5 0 0 1 2.5 2.5v8.45a2.5 2.5 0 0 1-2.5 2.5H5.25a2.5 2.5 0 0 1-2.5-2.5Z");
}

.yakkvabqx {
  cx: 10.75px;
  cy: 16.75px;
  r: 2px;
}

</style>
