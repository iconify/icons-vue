<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="dui_717ao"/><path class="ujx_k_azy"/><path class="kxe0zpavv"/><path class="ligsbjwqw"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:category-electrical" /></template>
<style>
.dui_717ao {
  d: path("M4.5 2h15v20h-15Z");
}

.kxe0zpavv {
  fill: currentColor;
  d: path("M8.5 12h7v3a1.5 1.5 0 0 1-1.5 1.5h-4A1.5 1.5 0 0 1 8.5 15Z");
}

.ligsbjwqw {
  d: path("M12 4.75h.01M12 19.25h.01");
}

.ujx_k_azy {
  d: path("M8.5 7.5h7v9h-7Zm0 4.5h7");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
