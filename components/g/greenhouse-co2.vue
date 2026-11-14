<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="xbo-ems7i"/><path class="aq-0apb2i"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:greenhouse-co2" /></template>
<style>
.aq-0apb2i {
  d: path("M15.5 21H20a2 2 0 0 0 0-4a3 3 0 0 0-5.5.5a2 2 0 0 0 1 3.5Z");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.xbo-ems7i {
  d: path("M11.244 20.5H3.5v-10L12 3.25l8.5 7.25v2.956M3.5 10.5h17M12 3.25V15.5");
}

</style>
