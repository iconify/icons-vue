<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><path class="p5c5vco1x"/><path class="i3x2w36av"/><circle class="yakkvabqx"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:folder-music-sharp" /></template>
<style>
.i3x2w36av {
  d: path("M12.75 16.75V10L15 11.5");
}

.p5c5vco1x {
  d: path("M2.75 7.25v-2.5h7.1l.6.8L11.55 7l.6.8h9.1v13.45H2.75v-2.5Z");
}

.x2cwu0gfd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.yakkvabqx {
  cx: 10.75px;
  cy: 16.75px;
  r: 2px;
}

</style>
