<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><path class="tysztybng"/><path class="elfo1ibsh"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:hacksaw-sharp" /></template>
<style>
.elfo1ibsh {
  d: path("M16.75 12.5h4.5v8.75h-4.5zm-13.25 1h13.25m-10.25 0V15m3-1.5V15m3-1.5V15");
}

.tysztybng {
  d: path("M3.5 16.5V4h16v8.5");
}

.x2cwu0gfd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
