<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="gp5t_abwy"/><path class="c8jwa2hjt"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:event-location" /></template>
<style>
.c8jwa2hjt {
  d: path("m12 6l1.029 2.084l2.3.334l-1.665 1.623l.393 2.291L12 11.25l-2.057 1.082l.393-2.291l-1.665-1.623l2.3-.334Z");
}

.gp5t_abwy {
  d: path("M12 21.5c-5-5.5-7.5-9-7.5-12a7.5 7.5 0 0 1 15 0c0 3-2.5 6.5-7.5 12Z");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
