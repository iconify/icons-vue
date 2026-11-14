<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="rudw3mbqf"/><path class="tazbn5b8j"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:exclusive-offer" /></template>
<style>
.rudw3mbqf {
  d: path("M3 9h18v4H3Zm1.5 4v6.5a2 2 0 0 0 2 2h11a2 2 0 0 0 2-2V13M12 13v8.5");
}

.tazbn5b8j {
  d: path("m12 2.75l1.029 2.084l2.3.334l-1.665 1.623l.393 2.291L12 8L9.943 9.082l.393-2.291l-1.665-1.623l2.3-.334Z");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
