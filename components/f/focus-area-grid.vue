<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="a77y5hm4t"/><path class="atv66_b1j"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:focus-area-grid" /></template>
<style>
.a77y5hm4t {
  d: path("M2.5 4.5h19v15h-19Zm4 3h.01m5.49 0h.01m5.49 0h.01M6.5 12h.01M12 12h.01m5.49 0h.01M6.5 16.5h.01m5.49 0h.01m5.49 0h.01");
}

.atv66_b1j {
  d: path("M10 12a2 2 0 1 0 4 0a2 2 0 1 0-4 0Z");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
