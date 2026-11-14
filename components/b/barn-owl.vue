<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="p_lj46xvb"/><path class="mtqo8zbik"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:barn-owl" /></template>
<style>
.mtqo8zbik {
  d: path("M6.5 10.5a2 2 0 1 0 4 0a2 2 0 1 0-4 0Zm7 0a2 2 0 1 0 4 0a2 2 0 1 0-4 0Zm-1.5 3V16");
}

.p_lj46xvb {
  d: path("M12 6C9 2.5 3.5 3.5 3.5 9.5C3.5 15 8 19 12 21c4-2 8.5-6 8.5-11.5c0-6-5.5-7-8.5-3.5Z");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
